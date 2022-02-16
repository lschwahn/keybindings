# About
hjkl everywhere - inspired by [madslundt/keybindings](https://github.com/madslundt/keybindings) and based on [Autokey](https://github.com/autokey/autokey).

Enables the "vimlike" usage of CAPSLOCK+hjkl as arrow keys in linux.

# Installation
1. Install [Autokey](https://github.com/autokey/autokey). 
2. Map CAPSLOCK to HYPER-Key (this is not possible by using autokey and has to be done by your own. For example with [Gnome Tweak Tool](https://wiki.ubuntuusers.de/GNOME_Tweaks/) or [Xmodmap](https://tbuss.de/posts/2021/5-capslock_as_vim_modifier/)
3. Clone this project to ~/.config/autokey/data
```
cd ~/.config/autokey/data
git clone https://github.com/lschwahn/keybindings.git
```

# Usage
Following keybindings are enabled:
| Shortcut                         | Output                           |
| -------------------------------- | -------------------------------- |
| CAPSLOCK + { i, j, k, l }        | { Up, Left, Down, Right }        |
| CAPSLOCK + CTRL + { i, j, k, l } | CTRL + { Up, Left, Down, Right }  |
| CAPSLOCK + CTRL + SHIFT + { i, j, k, l }  | CTRL + SHIFT + { Up, Left, Down, Right } |
| CAPSLOCK + { u, o }              | { PageUp, PageDown }                    |
| CAPSLOCK + { i, n }                   | { Home, End }             |
| CAPSLOCK + SHIFT + { i, n }                   | SHIFT + { Home, End }             |
| CAPSLOCK + CTRL + SHIFT + { i, n }                   | CTRL + SHIFT + { Home, End }             |
