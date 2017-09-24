# timelapse
Timelapse Scripts

# requirements
sudo apt-get install libfile-type-perl libterm-progressbar-perl ffmpeg paralell graphicsmagick libimage-exiftool-perl

add scripts to path
for s in `ls timelapse*`; do ln -s `pwd`/$s {dir in path}; done

# run
images are in the current direcory
timelapse {X}x{Y} {deflicker window} {deflicker runs} {fps}

resize:
full hd: 1920x1080(16:9), 1920x1440(4:3)
hd: 1280x720(16:9), 1280x960(4:3)

deflicker: 15 2

fps: 24
