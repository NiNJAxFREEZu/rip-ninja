# rip-ninja
Simple wrapper script for easy CD audio ripping like a true lazy ninja that you are.

## How it works?
Rips all the audio tracks from a CD into `wav` files.
Then, if you want to, converts them into other audio formats such as `mp3` or `flac`.

## How to use it?
Simply put a CD into your CD drive and launch the script.
You don't even have to mount a CD into a filesystem.  

```bash
$ rip-ninja [OUTPUT_AUDIO_FORMAT] [OUTPUT_DIRECTORY_PATH]
```

By default `OUTPUT_AUDIO_FORMAT` is set to `wav`, and `rip-ninja` will output files into current working directory.
You can use any audio conversion format that is supported by `ffmpeg`. So far I have only tested:
- `flac`
- `mp3`

## Dependencies
- cdparanoia (CD ripping)
- ffmpeg (`wav` conversion)

All dependencies are available in most major distros repositories.
