# Tmux custom config  
Main problem it often depends on the terminal how sequences are interpreted 
## Controll Sequences   
Meta key can be differen on differen systems
https://en.wikipedia.org/wiki/ANSI_escape_code

### modifier keys

  
## MacOS  
pleas note zsh doesn't have all control sequences definied as writtin in xterm 
"alt needs to be made to meta-key" 

The following controll seqences need to be added in preferences > Tastertur
ref.:https://www.xfree86.org/current/ctlseqs.html
```
shift-left ^[[2D
meta-shift-left ^[[4D

shift-right ^[[2C
meta-shift-right ^[[4C

shift-up ^[[2A
meta-shift-up ^[[4A

shift-down ^[[2B
meta-shift-down ^[[4B
```
