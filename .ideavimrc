set scrolloff=9
set number
set relativenumber
set tabstop=4 softtabstop=4
set shiftwidth=4
set expandtab
set smartindent
set colorscheme desert


" treat underscore as a word-separator in most programming files
augroup SnakeCase
  autocmd!
  " by FileType
  autocmd FileType python,c,cpp,cs,javascript,typescript,typescriptreact,json,html,css,ruby,lua,razor,cshtml,yaml setlocal iskeyword-=_
  " for extensions that don’t have their own FileType or use xml (csproj, props, targets)
  autocmd BufRead,BufNewFile *.csproj,*.props,*.targets setlocal iskeyword-=_
augroup END


" Colemak DH layout remappings for Vim
" This maps QWERTY positions to Colemak DH keys

" Movement keys (hjkl in QWERTY become mneo in Colemak DH)
noremap m h
noremap n j
noremap e k
noremap i l

" Other common keys remapped from QWERTY positions to Colemak DH
noremap r s
noremap s d
noremap t f
noremap g t
noremap f e
noremap d g
noremap u i
noremap y o
noremap o p
noremap p r
noremap j y
noremap l u
noremap k n

" Uppercase variants
noremap M H
noremap N J
noremap E K
noremap I L
noremap R S
noremap S D
noremap T F
noremap G T
noremap F E
noremap D G
noremap U I
noremap Y O
noremap O P
noremap P R
noremap J Y
noremap L U
noremap K N
