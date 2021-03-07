# rip-ninja
Simple script for easy CD audio ripping.

## How it works?
Rips all the audio tracks from a CD into `.wav` files and then it converts them into 320kbps `.mp3` files.  
Both `.wav` and `.mp3` files are saved into separate directories in `$HOME/Music/` - just the way I like it.

## How to use it?
Simply put a CD into your CD-drive and launch the script with one argument -- name of the album or whatever it is that you are ripping.  
For example:
```bash
$ ./rip-ninja Darude-Sandstorm
```
Will rip a CD and output: 
- `.wav` files into `$HOME/Music/wav/Darude-Sandstorm`
- `.mp3` files into `$HOME/Music/mp3/Darude-Sandstorm`.


## Dependencies
- cdparanoia (CD ripping)
- lame (`.wav` to `.mp3` conversion)
