---
layout: post
title: Setting up Linux again
---

sdfdsfFor quite sometime, I was really busy with my desk job. I am mostly involved in Java related technologies and churning out code on IntelliJ IDEA/Windows here but I was getting annoyed with the ecosystem outside IntelliJ. Setting up any software on windows and specially specific toolchain is painful. I manage a lot of CentOS servers though but the joy of using and developing on linux is very good.

So I decided to use a VM. I have seen VirtualBox crashing at weird times but I did decide to use it nevertheless. Until now, I was using my linux config and package list from the college laptop. I decided that it was too stale now and maybe I need to jump into making out my own system again.

I installed a vanilla Ubuntu 13.10 on the VM. There after it was easy

1. Once setup, installed the following packages/software

    * awesome
    * ZSH
    * terminator
    * Google Chrome
    * guake
    * exuberant-ctags
    * git
    * vim-gnome
1. Swap `Ctrl`/`Caps Lock` because my hands are configured that way. Plus it is quite easy to use vim and other tools that way. Use `xmodmap` to do that.
1. Setup oh-my-zsh and copy my old .zshrc files so that command line is all set
1. Setup quick shortcuts for guake (launch on _tilde_) and others as well
1. Make awesome as the default desktop manager
1. I decided to redo the vim config again. For the sane plugin management this time, I went with Vundle. It was very easy to set it up.

I am past the days of setting up different desktop managers, installing new distros, compiling packages from source, getting those shiny gnome-shell customizations etc. Now I want a fast,  lightweight, no-nonsense working system. I have vim, zsh, guake, chrome and awesome. I feel good now.
