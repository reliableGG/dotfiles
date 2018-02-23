""""""""""""""""""""""""""""""""""""""""
"       my own setting                 "
"                                      "
""""""""""""""""""""""""""""""""""""""""
set history=700
filetype plugin on
filetype indent on
set autoread
set wildmenu
set ruler
set cmdheight=2
colorscheme desert
"set backspace=eol,start,indent
"set whichwrap+=<,>,h,j
set autoindent
set shiftwidth=4
set tabstop=4
set nu
set ignorecase
set smartcase
set hlsearch
set incsearch
set lazyredraw
set magic
set showmatch
syntax enable
colorscheme desert
set background=dark
set foldmethod=indent

" encoding
set encoding=utf8
set fileencodings=utf8,gb18030,gbk,gb2312
set ffs=unix,dos,mac
set termencoding=utf-8

set nobackup
set nowb

""""""""""""""""""""""""""""
"       key map
"
""""""""""""""""""""""""""""
map <F2> :w<CR>
nmap <silent> <F3> :WMToggle<cr>
nnoremap <F4> :GundoToggle<CR>
map <F5> :NERDTreeMirror<CR>
map <F5> :NERDTreeToggle<CR>
map <F6> :Tlist<CR>
"nnoremap <F7> :tabp<CR>
""nnoremap <F9> :tabn<CR>
nnoremap <F7> gT
nnoremap <F9> gt
map <F10> :sh<CR>
map <F12> :q<CR>
nmap <Leader>nc :set nonu<CR>
nmap <Leader>no :set nu<CR>
nmap <Leader>xp :set paste<CR>
nmap <Leader>hl :nohl<CR>
nnoremap <silent> <C-l> :<C-u>nohlsearch<CR><C-l>

""""""""""""""""""""""""""""""""
" for plugin management:pathogen
""""""""""""""""""""""""""""""""
execute pathogen#infect()

""""""""""""""""""""""""""""""""
" for winManager
""""""""""""""""""""""""""""""""
let g:winManagerWindowLayout = "FileExplorer|TagList"
let g:winManagerWidth = 40

""""""""""""""""""""""""""""""
" showmarks setting
""""""""""""""""""""""""""""""
" Enable ShowMarks
let showmarks_enable = 1
" Show which marks
let showmarks_include ="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ"
" Ignore help, quickfix, non-modifiable buffers
let showmarks_ignore_type = "hqm"
" Hilight lower & upper marks
let showmarks_hlline_lower = 1
let showmarks_hlline_upper = 1

" For showmarks plugin
" hi ShowMarksHLl ctermbg=Yellow   ctermfg=Black  guibg=#FFDB72    guifg=Black
" hi ShowMarksHLu ctermbg=Magenta  ctermfg=Black  guibg=#FFB3FF    guifg=Black

""""""""""""""""""""""""""""""
"    for airline
"
""""""""""""""""""""""""""""""
if !exists('g:airline_symbols')
    let g:airline_symbols = {}
endif
let g:airline_symbols.space = "\ua0"
let g:airline_exclude_filename = []
let g:Powerline_symbols='fancy'
let g:airline_powerline_fonts=0
let g:bufferline_echo=0
let g:airline_left_sep = '»'
let g:airline_left_sep = '▶'
let g:airline_right_sep = '«'
let g:airline_right_sep = '◀'
let g:airline_symbols.crypt = '🔒'
let g:airline_symbols.linenr = '␊'
let g:airline_symbols.linenr = '␤'
let g:airline_symbols.linenr = '¶'
let g:airline_symbols.branch = '⎇'
let g:airline_symbols.paste = 'ρ'
let g:airline_symbols.paste = 'Þ'
let g:airline_symbols.paste = '∥'
let g:airline_symbols.whitespace = 'Ξ'
set laststatus=2
set t_Co=256
" file buffers tabline
let g:airline#extensions#tabline#enabled = 1
nnoremap [b :bp<CR>
nnoremap ]b :bn<CR>

" for powerline
"set guifont=PowerlineSymbols\ for\ Powerline
"set nocompatible
"set t_Co=256
"let g:Powerline_symbols = 'fancy'

let loaded_matchit = 0

" for gundo
let g:gundo_right = 1

" for ctrlp
set runtimepath^=~/.vim/bundle/ctrlp.vim

" for tabular
nmap <Leader>a :Tabularize /
vmap <Leader>a :Tabularize /

" for ctags and taglist
set tags=$PWD/tags
"let Tlist_Auto_Open = 1
let Tlist_Ctags_Cmd='/usr/local/bin/ctags'
let Tlist_Show_One_File=1
let Tlist_Exit_OnlyWindow=1
let Tlist_Use_Right_Window=1

