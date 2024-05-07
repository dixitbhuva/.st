# Simple Terminal by [suckless](https://suckless.org/)
Version: 0.9.2

## Patches pre applied are:
- Anysize - Terminal can follow any window size
- Scrollback - Scroll using mouse wheel
- Alpha - For transparency


## [Dependencies]
If you can make default st then you should be able to make this too no extra dependencies required.
Default this build of st comes with JetBrainsMono font.
For installing JetBrainsMono Nerd Font run this on terminal:
```
wget -P ~/.local/share/fonts https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/JetBrainsMono.zip \
&& cd ~/.local/share/fonts \
&& unzip JetBrainsMono.zip \
&& rm JetBrainsMono.zip \
&& fc-cache -fv
```

## Default KeyBindings:
|        Key            |        Action        |
|-----------------------|----------------------|
| scroll wheel up/down  |    Scroll up/down    |
| ctrl+shift++          |       zoom+          |
| ctrl+shift+-          |       zoom-          |
| ctrl+shift+backspace  |    zoom reset        |
| ctrl+shift+c          |       copy           |
| ctrl+shift+v          |       paste          |
| ctrl+shift+rightclick |       paste          |
For more keybindings checkout config.def.h 
