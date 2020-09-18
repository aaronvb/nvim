<img width="1072" alt="Screen Shot 2020-09-13 at 8 57 28 AM" src="https://user-images.githubusercontent.com/100900/93026102-379f1880-f59f-11ea-961f-be9564a15be0.png">

## Setup
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
```
> curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

`:PlugInstall` to install all plugins.
`:CocInstall coc-snippets` to install snippet support with coc.nvim

## Cheat sheet
Note: leader is `,`

`,w` fast save

`:W` sudo save

`,return` clear highlight

`# or *` searches current selection

`ctrl hjkl` move between windows

`,bd` close buffer

`,be` or `,o` opens buffer explorer

`,ba` close all buffers

`,l` next buffer

`,h` previous buffer

`,tn` tab  new

`,to` tab only

`,tc` tab close

`,tm` tab move

`,t,` tab next

`,tl` last tab

`,te` tab edit

`,cd` switch cwd to directory of open buffer

`,ss` toggle spell check

`,pp` toggle paste mode

`,g` ack

`,r` (visual) search and replace

`,cc` brings up ack cope

`,n` next search result

`,p` previous search result

`,j` or `ctrl p` ctrlP file

`,b` ctrlP buffer

`,f` ctrlP recently opened

`,nn` toggle nerd tree

`,nb` nerd tree from bookmark

`,nf` nerd tree reveal file

`ctrl s` multi select word

`,d` toggle git gutter

`shift k` coc toggle lookup documentation

`ctrl space` coc trigger completion

`[g ]g` coc to navigate coc diagnostics

`gd` coc jump to definition

`gy` coc jump to type definition

`gi` coc jump to implementation

`gr` coc jump to references

`,rn` coc symbol rename

`,f` coc format selected

`,qf` coc auto fix current line

`,ac` coc code action

`:Format` coc format file (happens automatically on save)

`:Fold` coc fold file

`:OR` coc auto add imports (happens automatically on save)

`space a` coc open diagnostics

`space e` coc open extensions

`space c` coc open commands

`space o` coc open outline

`space s` coc open symbols
