heat Sheet

## Global
`:help keyword` - open help for keyword
`:saveas file` - save file as
`:close` - close current pane
`K` - open man page for word under the cursor

## Cursor movement

`h` - move cursor left
`j` - move cursor down
`k` - move cursor up
`l` - move cursor right
`H` - move to top of screen
`M` - move to middle of screen
`L` - move to bottom of screen
`w` - jump forwards to the start of a word
`W` - jump forwards to the start of a word (words can contain punctuation)
`e` - jump forwards to the end of a word
`E` - jump forwards to the end of a word (words can contain punctuation)
`b` - jump backwards to the start of a word
`B` - jump backwards to the start of a word (words can contain punctuation)
`%` - move to matching character (default supported pairs: '()', '{}', '[]' - use :h matchpairs in vim for more info)
`0` - jump to the start of the line
`^` - jump to the first non-blank character of the line
`$` - jump to the end of the line
`g_` - jump to the last non-blank character of the line
`gg` - go to the first line of the document
`G` - go to the last line of the document
`5G` - go to line 5
`fx` - jump to next occurrence of character x
`tx` - jump to before next occurrence of character x
`Fx` - jump to previous occurence of character x
`Tx` - jump to after previous occurence of character x
`;` - repeat previous f, t, F or T movement
`,` - repeat previous f, t, F or T movement, backwards
`}` - jump to next paragraph (or function/block, when editing code)
`{` - jump to previous paragraph (or function/block, when editing code)
`zz` - center cursor on screen
`Ctrl + e` - move screen down one line (without moving cursor)
`Ctrl + y` - move screen up one line (without moving cursor)
`Ctrl + b` - move back one full screen
`Ctrl + f` - move forward one full screen
`Ctrl + d` - move forward 1/2 a screen
`Ctrl + u` - move back 1/2 a screen

## Editing
`r` - replace a single character
`J` - join line below to the current one with one space in between
`gJ` - join line below to the current one without space in between
`gwip` - reflow paragraph
`cc` - change (replace) entire line
`C` - change (replace) to the end of the line
`c$` - change (replace) to the end of the line
`ciw` - change (replace) entire word
`cw` - change (replace) to the end of the word
`s` - delete character and substitute text
`S` - delete line and substitute text (same as cc)
`xp` - transpose two letters (delete and paste)
`u` - undo
`Ctrl + r` - redo
`.` - repeat last command
