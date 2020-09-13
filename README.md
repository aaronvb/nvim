Base config taken from https://github.com/amix/vimrc

Install neovim:
```
> brew install neovim
```

Install pynvim support:
```
> python3 -m pip install --user --upgrade pynvim
```

Clone repo into `~/.config`
```
> cd ~/.config
> git clone git@github.com:aaronvb/nvim.git
```

Install plugings:
`:PlugInstall` to install all plugins.
`:CocInstall coc-snippets` to install snippet support with coc.nvim
