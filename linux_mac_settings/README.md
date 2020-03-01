## Vim을 IDE처럼 사용하기
https://blog.b1ue.sh/vim-ide/

## vim plugin
Plugin 'VundleVim/Vundle.vim'      " plugin installer package</br>
$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

Plugin 'scrooloose/nerdtree'       " show filelist</br>
Plugin 'vim-airline'               " show beautiful airline</br>
Plugin 'morhetz/gruvbox'           " vim theme gruvbox</br>
Plugin 'scrooloose/syntastic' "syntax checker</br>
Plugin 'Chiel92/vim-autoformat'</br>
Plugin 'Valloric/YouCompleteMe  https://github.com/ycm-core/YouCompleteMe</br>
Plugin 'rdnetto/YCM-Generator', { 'branch': 'stable'}</br>
Plugin 'davidhalter/jedi-vim'      " autocompletion for python</br>
Plugin 'vim-scripts/L9'            " basic plugin</br>
Plugin 'majutsushi/tagbar'         " show class, function, variable those have been used in current file (instead of 'taglist-plus')</br>
Plugin 'kien/ctrlp.vim'            " find file by name (instead of 'command-t')</br>
Plugin 'easymotion/vim-easymotion' " easily finding words</br>
Plugin 'sjl/gundo.vim'             " show editted code log looks like git branch</br>
Plugin 'tpope/vim-fugitive'        " git controller with vim (instead of 'vim-conflicted')</br>
Plugin 'airblade/vim-gitgutter'    " show git file status diff</br>
Plugin 'godlygeek/tabular'         " aligning multilines with same form (ex select lines + :Tab + / + <char></br>
Plugin 'Tuxdude/mark.vim'