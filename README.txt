===============================================================================
YUJA-DL
===============================================================================

Download videos and subtitles from *.yuja.com with this script.
Useful if your web-browser doesn't support streaming, or your PC is too weak
to run one in the first place. Also useful for archival.

I have a blog post on this over at https://xwx.moe/lib/ripping_hls_from_yuja.md

----------------------------------------
PRE-REQUISITES
----------------------------------------
You'll need:
	* curl
	* jq
	* ffmpeg
	* a shell 


----------------------------------------
USAGE
----------------------------------------
$ yuja-dl $VIDEO_URL $OUTPUT_NAME

$VIDEO_URL should be in the format of "https://*.yuja.com/V/Video=?v=*".
$OUTPUT_NAME will be the basename of the mp4 and srt files.


----------------------------------------
BORING STUFF
----------------------------------------
License is CC-0 
Author is Jaidyn Ann <jadedctrl@teknik.io>
https://git.feneas.org/detruota/yuja-dl.git
https://github.com/JadedCtrl/yuja-dl.git
