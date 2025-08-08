# Video Playback

## Overview
Rpg Tools supports the MPEG 1 video format(usually .mpg or .mpeg files)

According to the documentation of the `pl_mpeg` library I use:

Most [MPEG-PS](https://en.wikipedia.org/wiki/MPEG_program_stream) (`.mpg`) files containing MPEG1 Video ("mpeg1") and MPEG1 Audio Layer II ("mp2") streams should work with PL_MPEG. Note that `.mpg` files can also contain MPEG2 Video, which is
not supported by this library.

You can encode video in a suitable format using ffmpeg:

```
ffmpeg -i input.mp4 -c:v mpeg1video -q:v 0 -c:a libtwolame -b:a 224k -format mpeg output.mpg
```

`-q:v` sets a fixed video quality with a variable bitrate, where `0` is the 
highest. You may use `-b:v` to set a fixed bitrate instead; e.g. 
`-b:v 2000k` for 2000 kbit/s. Please refer to the 
[ffmpeg documentation](http://ffmpeg.org/ffmpeg.html#Options) for more details.

See https://github.com/phoboslab/pl_mpeg/blob/master/README.md for more details

### Playing videos
You can start videos via action "Start Video", via Cutscene or via Lua scripting


