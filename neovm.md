
### Installation (Linux)

```
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
chmod u+x nvim.appimage
#./nvim.appimage
sudo mv nvim.appimage /usr/bin/nvim
```

```
#sudo apt-get install neovim
#echo 'alias vim=neovim' >> ~/.bashrc   # or ~/.zshrc
```

* Install NvChad
`git clone https://github.com/NvChad/NvChad ~/.config/nvim --depth 1`

* Select theme
  - `SPC t h`, then select the theme you like (.e.g. catppuccin)
* Install syntax highlighting
  - `:TSInstall elixir`
* Install Font
  ```
  wget https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/JetBrainsMono.zip
  unzip JetBrainsMono.zip
  sudo mv JetBrainsMono*.ttf /usr/share/fonts/

  # Open vim and set the font
  vim
  :set guifont=JetBrainsMono\ Nerd\ Font
  ```


### Ref:
  - *** https://github.com/neovim/neovim/wiki/Installing-Neovim
  - https://github.com/neovim/neovim/wiki/Installing-Neovim
  - https://github.com/nvim-lua/kickstart.nvim
