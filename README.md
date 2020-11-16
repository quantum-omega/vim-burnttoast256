# vim-burnttoast256
A dark color scheme for 256-color terminals that I find easily readable.

This is the color theme I made for myself as I prefer to work on a dark background, namely black, without text that is too bright while still keeping a good contrast.  I based it heavily on http://www.vim.org/scripts/script.php?script_id=2140 and if you don't like my scheme you might like his. Check it out.

It includes colors for the normal text, the cursor and cursor line and column, search, status line, selection, line numbers, etc., as well as colors for syntax highlighting, diff mode, and some others.

The color scheme should be exactly the same in gvim as it is in vim and it has been tested for readability in both.  Required version written as 7.3, as it has colors for "CursorLineNr", but it probably will work on previous versions without any problems.

## Installation
To install, just put the file in your .vim/colors folder and add to your .vimrc:
set t_Co=256
colorscheme burnttoast256
