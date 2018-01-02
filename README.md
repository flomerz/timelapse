# timelapse
Timelapse Scripts

# requirements
sudo apt-get install libfile-type-perl libterm-progressbar-perl ffmpeg paralell graphicsmagick libimage-exiftool-perl gcp

# run
images are in the current direcory
timelapse {src-dir} {dest-dir} {X}x{Y}

resize:
full hd: 1920x1080(16:9), 1920x1440(4:3)
hd: 1280x720(16:9), 1280x960(4:3)

Name			Resolution		Link(Mbps)	Bitrate(Mbps) 	Video(kbps)	Audio(kbps)
16:9
240p			424x240			1.0			0.64			576			64
360p			640x360			1.5			0.96			896			64
432p			768x432			1.8			1.15			1088		64
480p			848x480			2.0			1.28			1216		64
480p HQ			848x480			2.5			1.60			1536		64
576p			1024x576		3.0			1.92			1856		64
576p HQ			1024x576		3.5			2.24			2176		64
720p			1280x720		4.0			2.56			2496		64
720p HQ			1280x720		5.0			3.20			3072		128
1080p			1920x1080		8.0			5.12			4992		128
1080p HQ		1920x1080		12.0		7.68			7552		128
1080p Superbit	1920x1080		N/A			20.32			20000		320
4:3
240p			320x240			1.0			0.64			576			64
360p			480x360			1.2			0.77			704			64
480p			640x480			1.5			0.96			896			64
480p HQ			640x480			2.0			1.28			1216		64
576p			768x576			2.3			1.47			1408		64
576p HQ			768x576			2.5			1.60			1536		64
720p			960x720			3.0			1.92			1856		64
720p HQ			960x720			4.0			2.56			2432		128
1080p			1440x1080		6.0			3.84			3712		128
1080p HQ		1440x1080		9.0			5.76			5632		128
1080p Superbit	1440x1080		N/A			20.32			20000		320
