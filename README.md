# encode_script_handbrake
Bash script that will allow you to encode all videos in your Watch folder with just one click.

It takes video files from Watch folder (by default: usr/Decuments/Watch) and starts encoding them using HandbrakeCLI, so you have to install it first. Encoded videos are placed in the Output folder (by default: usr/Decuments/Output) along with log file. After that a source file from Watch folder will be deleted. 

You can change your Watch/Output folder location by editing line 25:
  FILES="/Users/samael/Documents/Watch/*"

You can change your encoding settings by editing line 26:
  PRESET="-e x264 -q 20 --x264-preset veryfast"

Supported file formats: .mp4, .avi, .mov, .mkv

More on encoding settings of HandbrakeCLI:
https://trac.handbrake.fr/wiki/CLIGuide 

Cheers! ;-)

