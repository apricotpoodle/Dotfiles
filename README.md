# Dotfiles

My full development environment 🚀 

Insipired from Flo Slv

https://github.com/Flo-Slv/Dotfiles

## How I manage my dotfiles

### Purpose

The idea is to keep all my dotfiles in the same folder.<br>
In this way, I can easily manage it with git / github to install it in a new computer.<br><br>

Moreover, I don't really like how Linux organize all dotfiles and apps installation. If you look into your `$HOME` folder, some of them are in `~/.config` directory, others in their own folder, and others like `.zshrc` in the `$HOME` directly.<br><br>

I use *DEBIAN 12 Bookworm* as an operating system.<br>
I use *gnome* as a window manager.<br>
I, not yet, use *TMUX* as a terminal multiplexer.<br>
I use *NEOVIM* as an editor.<br><br>

My workflow is pretty basic and I tend to not use my mouse. Even in Firefox thanks to the Vimium extension !
<br><br>

So, in the end, I created a simple folder called `Fab` in my `$HOME`.<br>
Inside it, there is my `Dotfiles` directory and all other folders I use every day. Everything is clean and my mind is in peace xD<br><br>

To deal with that and keep my dotfiles in the same folder, I use `stow`, which is a symlink manager.<br><br>

Here is the process if you want the same environment ! 🚀<br><br><br />

