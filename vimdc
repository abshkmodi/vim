colorscheme badwolf " awesome colorscheme. color (eg badwolf.vim should be in ~/.vim/colors
syntax enable " enable syntax highlighting. show parts of text in another font or color
set tabstop=2 " number of visual spaces which are shown when vim reads a tab character
set softtabstop=2 " number of spaces inserted when you hit tab 
set expandtab " don't use actual tab, use spaces instead
set number " show line numbers
set cursorline " highlight current line. puts a underscore on the current line
filetype indent on " load filetype-specific indent files. Eg - If there is a ~/.vim/indent/python.vim it will get loaded every time you open a *.py file.
set wildmenu " visual autocomplete for command menu
set lazyredraw " redraw only when we need to. leads to faster macros
set showmatch " highlight matching parentheses - [{()}]
set incsearch           " search as characters are entered
set hlsearch            " highlight matches

map <C-M> :!ctags -R -o /home/ubuntu/.vim/tags/rkpythonscripts /home/ubuntu/sdmain/src/scripts;ctags -R -o /home/ubuntu/.vim/tags/rkpython /home/ubuntu/sdmain/src/py;ctags -R -o /home/ubuntu/.vim/tags/rkcpp /home/ubuntu/sdmain/src/cpp<CR>
set tags+=/home/ubuntu/.vim/tags/rkpythonscripts
set tags+=/home/ubuntu/.vim/tags/rkpython
set tags+=/home/ubuntu/.vim/tags/rkcpp
set statusline+=%F
