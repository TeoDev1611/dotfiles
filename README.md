<h1 align="center">
  Teo Dev Personal Dotfiles with dotly 💻 
</h1>

## Installation



## Restore your Dotfiles manually

* Install git
* Clone your dotfiles repository `git clone https://github.com/teodev1611/dotfiles $HOME/.dotfiles`
* Go to your dotfiles folder `cd $HOME/.dotfiles`
* Install git submodules `git submodule update --init --recursive modules/dotly`
* Install your dotfiles `DOTFILES_PATH="$HOME/.dotfiles" DOTLY_PATH="$DOTFILES_PATH/modules/dotly" "$DOTLY_PATH/bin/dot" self install`
* Restart your terminal
* Import your packages `dot package import`

## Restore your Dotfiles with script

Using wget
```bash
bash <(wget -qO- https://raw.githubusercontent.com/CodelyTV/dotly/HEAD/restorer)
```

Using curl
```bash
bash <(curl -s https://raw.githubusercontent.com/CodelyTV/dotly/HEAD/restorer)
```

> .dotfiles created using <a href="https://github.com/CodelyTV/dotly">🌚 dotly</a>
