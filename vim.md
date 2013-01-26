# VIM

* text editor like notepad/gedit/word
* found on any linux distribution
* over ssh/gui not required
* modal editor: different modes


### Commands
* vim <filename> : open file in vim
* vimtutor : vim tutorial


### Insert mode:
* i : insert normally
* o : open a line below cursor
* O : open a line above cursor


### Command mode:
* press ESC


### Last line mode/command mode:
* to enter longer strings of commands


### Standard movement: (command mode)
* h : <-
* j : is down
* k : is up
* l : ->
* 0 : beginning of line
* $ : end of line
* w : forward one word
* b : backward one word
* G : end of file
* gg : beginning of file
* `. : last edit
* combinations 5w : move five words forward, 5j for 5 lines


### Search and replace
* /<search forwards>
* ?<search backwards>
* n , N for direction
* :%s/text/replacement/gc g -> global c->confirmation
**  wildcards in text eg / escape using \/


### Editing
* d to delete
* dw to delete word
* d0 -> cursor to beginning
* d$ -> cursor to end
* etc … 
* u -> undo
* Ctrl + r -> redo


### Copy pasting [visual mode]
* v : one character at a time
* V : one line at a time
* ctrl + V : select in columns
* p : paste text after current line(or cursor)
* P : paste text in current line(or cursor)
* y : yank (copy) into copy buffer


### Save
* :w : save
* :w filename : save different file name
* :wq [filename] : save and quit
* :q! : quit without saving


### word completions
* ctrl + p / ctrl + n
* :ab <abbr> <abbreviation> : everywhere even new file <abbr><space> gives <abbreviation>
* :iab <abbr> <abbreviation> : only in insert mode
* ctrl+v to avoid abbreviation


### ETC.
* :shell
* :help
* dd : delete current line
* yy : copy current line
* :split : split horizontally
* :vsplit <filename> split vertically
