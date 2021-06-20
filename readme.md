# Dotfiles
My dotfiles for Mac. These are based on the [dotbot bootstrapper](https://github.com/anishathalye/dotbot). This readme contains information on how to setup the dotfiles as well as other processes which needs to be done.

# Installation process
On a new mac, start by running 

``` sh
xcode-select --install
```

To get git and stuff.

## Setting up git properly
Setting up git with ssh is described in [this guide](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent). 

Create a new ssh key by doing:

``` sh
ssh-keygen -f ~/.ssh/github_rsa
```

Then copy the key by doing:

``` sh
cat ~/.ssh/github_rsa.pub| pbcopy
```

Finally, upload the key to: https://github.com/settings/keys

## Cloning the repo
After setting up git, clone the repo by doing:

``` sh
git clone git@github.com:SimenHolmestad/.dotfiles.git
```

## installing the dotfiles
To setup everything correctly, do
``` sh
sh install
```

This might take some time.
# More stuff to do
Below are some configurations steps which were hard to automate.
## Finish configuring rectangle
Open rectangle app and import the [rectangle preferences json file](rectangle_preferences.json).
## Setup intellij
Make sure [ideavim](https://plugins.jetbrains.com/plugin/164-ideavim/), [ideavim-easymotion](https://plugins.jetbrains.com/plugin/13360-ideavim-easymotion) and [AceJump](https://plugins.jetbrains.com/plugin/7086-acejump) are installed.
## Install Adobe software
If necessary.
