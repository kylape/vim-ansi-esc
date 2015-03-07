#AnsiEsc
###Ansi Escape Sequence Visualization

*Author*:  Charles E. Campbell, Jr.  <NdrOchip@ScampbellPfamily.AbizM> (remove
NOSPAM from Campbell's email first)

*Copyright*: (c) 2004-2014 by Charles E. Campbell, Jr.  The [VIM
LICENSE](http://vimdoc.sourceforge.net/htmldoc/uganda.html) applies to
AnsiEsc.vim and AnsiEsc.txt except use "AnsiEsc" instead of "Vim".  No
warranty, express or implied.  Use At-Your-Own-Risk.

Description from [the plugin's page on
vim.org](http://www.vim.org/scripts/script.php?script_id=302):

> Files with ANSI escape sequences look good when dumped onto a terminal that
accepts them, but heretofore have been a distracting clutter when edited via
vim.  The AnsiEsc.vim file, when sourced with vim 7.3 or later, will conceal
Ansi escape sequences but will cause subsequent text to be colored as the
escape sequence specifies. 

> You need to have a vim with conceal mode enabled; use `has("conceal")` to
> find out if the vim you're using has that feature. 

> Without that conceal feature or with vim versions earlier than 7.3, the best
that can be done is to suppress Ansi escape sequences with "Ignore"
highlighting.  AnsiEsc.vim v2 does that. 
