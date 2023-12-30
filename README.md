# My key binding guide 2024

## General

- `cmd+shift+p` open command palette
- `cmd+f` find
  - `enter` next
  - `shift+enter` previous
- `cmd+r` replace
- `cmd+(number)` switch to tab number
- `shift+escape` focus on editor
- `cmd+w` close tab
- `cmd+shift+w` close another tab
- `cmd+e` create temp file
- `space+h` show hover (use arrow for scroll)

## Navigation

- ### window

  - `cmd+shift+e` open explorer
  - `cmd+shift+f` open search
  - `cmd+shift+g` open git
  - `cmd+shift+d` open debug
  - `cmd+shift+o` open output
  - `cmd+shift+m` open problems
  - `cmd+shift+t` open terminal
  - `cmd+shift+y` open debug console

## Editor

- ### Insert mode

  - `shift+tab` accept inline suggestion
  - `shift+enter` accept code suggestion (trigger suggestion)
  - `w` move the cursor to the beginning of the next word.
  - `b` move the cursor to the beginning of the previous word.
  - `e` move the cursor to the end of the current word.
  - `gg` go to top of file
  - `G` go to bottom of file
  - `$` go to end of line
  - `^` go to start of line
  - `0` go to start of line
  - `%` go to matching bracket

- ### Normal mode

  - `.` repeat last command
  - `>` indent
  - `<` unindent
  - `space+a` quick fix
  - `space+e` quick open file
  - `space+g` go to line number
  - `space+s` quick outline view
  - `space+f` all symbol search
  - `space+p` pin editor
  - `space+P` unpin editor
  - `gc` toggles line comment
  - `gC` toggles block comment
  - `shift+j` Join lines
  - `space+t` run task

- ### Surround

  - `cs(old)(new)` change surround from old to new
  - `ds(delete)` delete surround
  - `ys(scope)(add)` add surround on scope
  - `(selection)S(new)` add surround on visual selection

- ### Jump

  - `}` jump to next paragraph
  - `{` jump to previous paragraph
  - `gd` Go to definition
  - `gi` Go to implementation
  - `gr` Go to references
  - `gt` Back to previous tab
  - `gT` Forward to next tab
  - `gh` Go back
  - `gl` Go forward

- #### Debug

  - `space+b` toggle breakpoint (not implement)
  - `space+l` toggle log point (not implement)
  - `space+c` debug continue (not implement)
  - `space+n` debug next (not implement)
  - `space+C` debug stop (not implement)
  - `space+r` debug restart (not implement)
  - `space+i` debug step into (not implement)
  - `space+I` debug step out (not implement)

- ### Visual mode

  - `option+click` add cursor
  - `option+shift+click` box visual mode
  - `option+up` add cursor up
  - `option+down` add cursor down
  - `option+left` expand selection
  - `option+right` shrink selection
  - `option+d` select next word
  - `option+shift+d` select prev word
  - `option-l` select all occurrences of the current selection

## Terminal

- `cmd+n` open new terminal
- `cmd+w` close current terminal

## Explorer

- `enter` open file
- `cmd+n` new file
- `cmd+N` new folder
- `cmd+d` delete
- `cmd+r` rename
