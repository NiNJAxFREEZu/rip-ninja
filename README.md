# rip-ninja
Simple script for easy CD audio ripping like a true lazy ninja that you are.

## How it works?
Rips all the audio tracks from a CD into `.wav` files and then converts them into 320kbps `.mp3` files.  
Both `.wav` and `.mp3` files are saved into separate directories in `$HOME/Music/` - just the way I like it.

## How to use it?
Simply put a CD into your CD-drive and launch the script with one argument - name of the album (or whatever it is that you are ripping).  
For example:
```bash
$ ./rip-ninja Darude-Sandstorm
```
Will rip a CD and output: 
- `.wav` files into `$HOME/Music/wav/Darude-Sandstorm/`
- `.mp3` files into `$HOME/Music/mp3/Darude-Sandstorm/`.

## But I would like to save my files into different directory!
To keep the script super simple and bug-free, you can customize some stuff like output paths or mp3 bitrate via editing the source code in the dedicated section at the beginning of the script. It sounds scary but it's actually super `easy`.


## Dependencies
- cdparanoia (CD ripping)
- lame (`.wav` to `.mp3` conversion)

All dependencies are available in most major distros repositories.
