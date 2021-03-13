# rip-ninja
Simple script for easy CD audio ripping like a true lazy ninja that you are.

## How it works?
Rips all the audio tracks from a CD into `.wav` files and then converts them into `.flac` files.  
Both `.wav` and `.flac` files are saved into separate directories in `$HOME/Music/` by default - just the way I like it.

## How to use it?
Simply put a CD into your CD drive and launch the script with one argument - name of the album (or whatever it is that you are ripping).
You don't even have to mount a CD into a filesystem.  

For example:
```bash
$ ./rip-ninja Master-Of-Puppets
```
Will rip every track from a CD and output: 
- `.wav` files into `$HOME/Music/wav/Master-Of-Puppets/`
- `.flac` files into `$HOME/Music/flac/Master-Of-Puppets/`.

## But what if I would like to save my files into different directory?!
To keep the script super simple and bug-free, you can customize some output paths via editing the source code in the dedicated section at the beginning of the script. It sounds scary but it's actually super `easy`.

## Dependencies
- cdparanoia (CD ripping)
- ffmpeg (`.wav` to `.flac` conversion)

All dependencies are available in most major distros repositories.
