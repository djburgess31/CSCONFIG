# MMConfig
Movie Making Config

# Video Settings
Resolution: 1920 x 1080 16:9\
Color Mode: Television\
Global Shadow Quality: High\
Texture Detail: High\
Effect Detail: High\
Shader Detail: High\
MSAA: 8x\
FXAA: On\
Texture Filtering Mode: Anisotropic 16x

# Launch Options
-novid -nojoy -high -fullscreen -refresh 240 -tickrate 128 -limitvsconst -forcenovsync +r_dynamic 0 +mat_disable_fancy_blending 1 +cl_forcepreload 1 +exec autoexec.cfg

# Instructions
Before: "ae", "mm" to exec autoexec and moviemaking configs

Demo Instructions
1. Go into demo
2. Find player ids using "listplayers"
3. Exit demo
4. Configure commands\
	"mirv_pov \<id\>" - a pov view of player\
	"mirv_replace_name filter add \<userid\> \<newname\>" - replaces names\
	"mirv_deathmsg filter add attackerMatch=!x\<XUID\> victimMatch=!x\<XUID\> block=1 lastRule=1" - filters out other death messages
5. Setup streams using "configstreams"
6. Edit streams using presets:\
	"simple" - hud black/white streams, world + viewmodel stream\
	"normal" - hud black/white streams, world stream, viewmodel stream, green screen stream\
	"normal2" - hud black/white streams, world stream, viewmodel black/white streams, black/white screen stream\
	"depth" - hud black/white streams, world stream, viewmodel stream, green screen stream, depth streams
7. Return to demo\
8. Record using commands\
	"smoothdemo" - smooths demo for better recording\
	"mirv_deathmsg lifeTime default/\<time\>" - sets the display time of death messages\
	"mirv_streams record voices 1" - turns on recording of team comms\
	"recorddemo" - starts record\
	"stoprecord" - stops record

Video Instructions\
1. Drag .tga file into Virtualdub
2. Set:\
	frame rate: 600\
	audio: no audio\
	compression: lagarith lossless
3. Save video

Editing Instructions
	