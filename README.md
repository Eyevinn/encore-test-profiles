# Encore test profiles
Some basic transcoding profiles for testing encores.

## Transcoding profiles
| Name | Description |
| --- | --- |
| program | x264 ABR ladder with five rungs, stereo and surround audio, thumbnails, thumbnail map |
| program-x265 | x265 ABR ladder with five rungs, stereo and surround audio, thumbnails, thumbnail map |
| program-kf | x265 ABR ladder with five rungs, stereo and surround audio, thumbnails, thumbnail map, option to override keyframe injections |
| archive | DNXHD 185Mbit/s encode with pcm audio |
| x264_1080p_slow | x264, 2-pass VBR ~3100kbit/s, 1920x1080, 25fps, 96 frames GOP, preset slow |
| x265_1080p_slow | x265, 2-pass VBR ~2600kbit/s, 10bit, 1920x1080, 25fps, 96 frames GOP, preset slow |
| x264_1080p_medium | x264, 2-pass VBR ~3100kbit/s, 1920x1080, 25fps, 96 frames GOP, preset medium |
| x265_1080p_medium | x265, 2-pass VBR ~2600kbit/s, 10bit, 1920x1080, 25fps, 96 frames GOP, preset medium |

The profiles program, program-x265, and archive are based on the test profiles present in the encore github repository under
[src/test/resources/profile](https://github.com/svt/encore/tree/master/src/test/resources/profile).
