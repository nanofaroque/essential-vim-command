### Installing neovim: 
 Please go here and follow the instruction based on your operating system
  https://github.com/neovim/neovim/wiki/Installing-Neovim
  
  
### Installing nvim-tree.lua

Open your `vim ~/.vimrc` file if you dont have any, please create one. 

Add the dependency like below: 
```
call plug#begin() 
" The default plugin directory will be as follows:
"   - Vim (Linux/macOS): '~/.vim/plugged'
"   - Vim (Windows): '~/vimfiles/plugged'
"   - Neovim (Linux/macOS/Windows): stdpath('data') . '/plugged'
" You can specify a custom plugin directory by passing it as the argument
"   - e.g. `call plug#begin('~/.vim/plugged')`
"   - Avoid using standard Vim directory names like 'plugin'

" Make sure you use single quotes

" Shorthand notation; fetches https://github.com/junegunn/vim-easy-align
Plug 'junegunn/vim-easy-align'
" requires
Plug 'kyazdani42/nvim-web-devicons' " for file icons
Plug 'kyazdani42/nvim-tree.lua'
call plug#end()
```
Save it. 
In between the start and end, you have the plugin to install. 

Now run the command below: 
`vim ~/.vimrc`
`:PlugInstall`
to update: 
`vim ~/.vimrc`
`:PlugUpdate`
