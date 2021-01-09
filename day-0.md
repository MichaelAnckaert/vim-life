# VIM Life - Day 0

This is day 0 of your VIM life. Today, you'll learn how to install VIM on your computer, how to start vim, and how to quit the application. 


## Installing VIM

### Linux users

If you are using Linux there is good chance you already have VIM available on your computer. Open a terminal and run the `vim` command. If everything is ok, you will see VIM start and 


### Mac OS users

In some cases you will need to install or update VIM on your computer depending on the operating system version.

The easiest way for a Mac OS User to get the latest version of VIM is to install the  [`Homebrew`](https://brew.sh/) package manager.
You can install `Homebrew` in a simple one liner in your terminal of choice:

```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```

From there you should be able to install the [`LTS`](https://formulae.brew.sh/formula/vim) version of VIM by opening a terminal and run: `brew install vim`

Finally you can open up your terminal of choice and open VIM by simply by writing `vim` and pressing enter.

### Windows users

[`Best guide I could fined online`](https://www.freecodecamp.org/news/vim-windows-install-powershell/)


## Starting VIM

To start VIM from the terminal, you simply enter the **vim** command in the terminal and press *<ENTER>*. 


## Leaving VIM

Despite the many jokes about being stuck in VIM forever, or ony being to close VIM by restarting your computer, leaving VIM is very simple. 

First, make sure you are in *NORMAL* mode, so press the *<ESC>* key a couple of times. Then press the **:** key and type **q!** followed by *<ENTER>*. 

### What did I just do?!?

You're probably wondering what all this black magic is, **:q!<ENTER>**, *"I'm going back to VSCode!*...

WAIT! Don't give up already! Head over to [Day 1](day-1.md) to start your journey!


