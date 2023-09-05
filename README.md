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

# Development Environment

:warning: _January 2023_ :warning:<br />
► only tested and approved on:

- Debian 12 Bookworm x86_64
<br /><br />

At first, this repo was for my own usage but I tried to comment every step so you can follow my instructions and take inspiration from my repo :blush:

I assume you start with a fresh installation of Ubuntu 22.04.1 LTS

I also assume you know basics of VIM like how to edit and save/quit :stuck_out_tongue_closed_eyes:

Each step respect a specific order. Please respect same order !

The complete installation take around ~60 min depending power of the computer and your knowledges to understand what I am doing.

---
1. Dependencies

   1. [Folder structure](#create-folder-structure)
   2. [Install packages](#install-dependencies)

2. [Oh-my-zsh](#oh-my-zsh---install)

3. More dependencies

   1. [Node.js via nvm](#nodejs-via-nvm---install)
   2. [Rust and Cargo](#rust---install)

4. Neovim

   1. First option: install and config Neovim from [flo-neovim-install.sh](#first-option-install-and-config-neovim-from-a-bash-script)
   2. Second option:
      1. [Install from sources](#second-option-neovim---install-from-sources)
      2. [Packer as plugin management](#packer---install)
      3. [Neovim config](#neovim---config)

5. Tmux

   1. [Install from sources](#tmux---install-from-sources)
   2. [Tmux config](#tmux---config)

6. [zsh config](#zsh---config)

7. [Alacritty](#alacritty---install) as terminal

8. [Hack Nerd Font](#hack-font---install)

9. [Starship](#starship---install) custom zsh prompt

10. [fzf](#fzf---install)

11. [Rofi](#rofi---config)

12. [Polybar](#polybar---install-and-config)

13. [I3wm](#i3-wm---config) as windows manager

14. [Btop](#btop---install)

15. Git

    1. [Git config](#git---config)
    2. [Git CZ](#git-cz---install-and-config)
    3. [GitUI](#gitui---install-and-config)

16. [Insomnia](#insomnia---install)

17. [Notion](#notion---install)

18. MongoDB

    1. [MongoDB](#mongodb---install)
    2. [MongoDB Compass](#mongodb-compass---install)

19. [Glow](#glow---install)

20. [SSH](#ssh---github-keys)

21. [~/Flo/Dotfiles as git repo](#flodotfiles-as-git-repo)

22. [AppImageLauncher](#appimagelauncher---install)

23. [PrismaStudio](#prisma-studio---install)

24. [Stow](#stow)

25. [Troubleshooting](#troubleshooting)

---

