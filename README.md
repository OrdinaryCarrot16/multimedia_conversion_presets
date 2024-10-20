# multimedia_conversion_presets
A collection of scripts for re-encoding existing media (mostly videos, and music) with various 'enhancements' hand-picked by me, for the simplicity and convenience of others and myself.

I tried to make the experience for users as simple as I could, but the user will probably still need a decent amount of knowledge with computers to figure out how to use them. It should mostly just be a case of installing the required software, and adding some of them to your PATH (to access it from your shell). The problem might arise in the AviSynth+ external plugins, but I will try to write instructions in the future.

## Software Required (User):
- [PowerShell](https://github.com/PowerShell/PowerShell/releases) (for running the scripts)
- [FFMpeg](https://github.com/BtbN/FFmpeg-Builds/releases) (for pretty much everything encoding related)
- [MakeMKV](https://www.makemkv.com/download/) (for ripping DVDs and Blu-Rays)
- [AviSynth+](https://github.com/AviSynth/AviSynthPlus/releases/) (for scripting more advanced edits)
  - [FFMS2](https://github.com/FFMS/ffms2/releases) (File Input & Output)
  - [Neo VagueDenoiser](https://github.com/HomeOfAviSynthPlusEvolution/neo_Vague_Denoiser/releases) (Light Denoise)
  - [HQDN3D](https://github.com/Asd-g/AviSynth-hqdn3d/releases) (Light Denoise? Still testing.)
  - [aSharp](https://github.com/Asd-g/AviSynth-ASharp/releases) (Sharpening)
- [MKVToolNix](https://mkvtoolnix.download/downloads.html) (WEBM Muxing)

## Software I Used (that isn't listed in 'Software Required'):
- [AvsPmod](https://github.com/gispos/AvsPmod/releases) (for previewing scripts)

## Formats, Encoders, and Parameters

### CD

- Audio Encoding: WAVE > Vorbis
- Audio Bitrate (ABR): 240k

### DVD

- Video Encoding: MPEG2 > VP8
- Audio Encoding: ??? > Opus
- Resolution: 480p > 480p (Decent quality)
- Video Bitrate (CRF): 20
- Audio Bitrate (VBR): 160k

### Blu-Ray

- Video Encoding: H.264 > VP8 (Faster than VP9, and better optimized for resolutions under 1080p)
- Audio Encoding: ??? > Opus
- Resolution: 1080p > 720p (Good quality; more space savings)
- Video Bitrate (CRF): 20
- Audio Bitrate (VBR): 192k

### Digital Music

- Audio Encoding: WAV/FLAC/MP3/M4A/OGG (depends on provider) > Vorbis
- Audio Bitrate (ABR): 240k

### Digital Video

- Video Encoding: MP4/WEBM (Depends on provider) > VP8
- Audio Encoding: AAC/OPUS > Vorbis
- Resolution: ??? (widely varies) > 480p
- Video Bitrate (CRF): 20
- Audio Bitrate (VBR): 160k
