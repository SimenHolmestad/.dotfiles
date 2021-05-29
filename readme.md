# Dotfiles
My dotfiles for Mac. These are based on the [dotbot bootstrapper](https://github.com/anishathalye/dotbot).

I haven't got around to run the dotfiles from scratch yet, so they will probably be updated.

## How to install
On a new mac, start by running 

``` sh
xcode-select --install
```

To get git and stuff. Then run

``` sh
sh install
```

This might take some time.
# More stuff to do
Below are some configurations steps which were hard to automate.
## Finish configuring rectangle
Open rectangle app and import the [rectangle preferences json file](rectangle_preferences.json).
## Configure github using ssh
Create a new ssh key by doing:

``` sh
ssh-keygen -f ~/.ssh/github_rsa
```

Then copy the key by doing:

``` sh
cat ~/.ssh/github_rsa.pub| pbcopy
```

Finally, upload the key to: https://github.com/settings/keys
## Install Adobe software
If necessary.
