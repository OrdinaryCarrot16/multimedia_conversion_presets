# multimedia_conversion_presets
A collection of scripts for re-encoding existing media (mostly videos, and music) with various 'enhancements' hand-picked by me, for the simplicity and convenience of others and myself.

## Software Required (User):
- [FFMpeg](https://github.com/BtbN/FFmpeg-Builds/releases) (for pretty much everything encoding related)
- [MakeMKV](https://www.makemkv.com/download/) (for ripping DVDs and Blu-Rays)
- [AviSynth+](https://github.com/AviSynth/AviSynthPlus/releases/) (for scripting more advanced edits)

## Software I Used:

- [FFMpeg](https://github.com/BtbN/FFmpeg-Builds/releases)
- [MakeMKV](https://www.makemkv.com/download/)
- [AviSynth+](https://github.com/AviSynth/AviSynthPlus/releases/)
- [AvsPmod](https://github.com/gispos/AvsPmod/releases)

## Formats, Encoders, and Parameters

### CD

- Audio Encoding: WAVE > Vorbis
- Audio Bitrate (ABR): 240k

### DVD

- Video Encoding: MPEG2 > VP8
- Audio Encoding: ??? > Vorbis
- Resolution: 480p > 480p
- Video Bitrate (CRF): TBA
- Audio Bitrate (VBR): 256k

### Blu-Ray

- Video Encoding: H.264 > VP9
- Audio Encoding: ??? > Opus
- Resolution: 1080p > 720p
- Video Bitrate (CRF): TBA
- Audio Bitrate (VBR): 192k

### Digital Music

- Audio Encoding: WAV/FLAC/MP3/M4A/OGG (depends on provider) > Vorbis
- Audio Bitrate (ABR): 240k

### Digital Video

- Video Encoding: MP4/WEBM (Depends on provider) > VP8
- Audio Encoding: AAC/OPUS > Vorbis
- Resolution: ??? (widely varies) > 480p
- Video Bitrate (CRF): 24
- Audio Bitrate (VBR): 160k
