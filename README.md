# Zathura Config
 
Minimal Zathura setup with dark mode and Vim motions.
 
## Install
 
```bash
sudo apt install zathura zathura-pdf-poppler
mkdir -p ~/.config/zathura
cp zathurarc ~/.config/zathura/zathurarc
```
 
## Set as Default PDF Viewer
 
```bash
xdg-mime default org.pwmt.zathura.desktop application/pdf
```
 
## Keybindings
 
| Key | Action |
|-----|--------|
| `j/k` | Scroll down/up |
| `h/l` | Scroll left/right |
| `d/u` | Half page down/up |
| `Ctrl+f/b` | Full page down/up |
| `J/K` | Next/previous page |
| `gg/G` | First/last page |
| `zi/zo` | Zoom in/out |
| `zz/zw` | Best-fit/fit to width |
| `/` `?` | Search forward/backward |
| `n/N` | Next/previous result |
| `i` | Toggle dark mode |
| `r/R` | Reload/rotate |
| `q` | Quit |
 
## Theme
 
[Catppuccin Mocha](https://github.com/catppuccin/catppuccin)
