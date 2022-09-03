# ghrvimrc
**my vim configuration**

Highly Recommended: [VimGolf: Real Vim ninjas count every keystroke](https://www.vimgolf.com/)

An example:

Input File:

```
A HAPPY END WITH YEAR 2013 !
```

Output File:

```
A HAPPY NEW YEAR 2014 !
```

Beginners will do:

```
llllllllllxxxxxxxxiNEW<ESC>lllllllllllxi4<ESC>:wq!
```

Master will do:

```
ww8sNEW<Esc><C-A>ZZ
```

vim shortcuts

```
hjkl "move the cursor"
ZQ=:q! "force exit"
ZZ=:wq "write and quit"
<ESC> "escape and enter the normal mode"
x "delete current character"
X "delete character before"
^f "Page Down"
^b "Page Up"
^d "Half Page Down"
^u "Half Page Up"
^e "scroll one line down"
^y "scroll one line up"
i "insert"
e "next end of a word"
w "next start of a word"
W "next WORD, sep by BLANK"
b "front start of a word"
ge "front end of a word"
yy "copy a line"
Y "copy a line"
<num>yy "copy <num> lines from current line"
p "paste, or put"
dd "delete a line"
A "insert text after the end of the line"
a "append after the cursor"
$ "go to end of a line"
gg "go to start of the file"
G "go to the end of the file"
xxxG "go to line xxx"
xxx% "go to location xxx%"
zz "move the current line to the center of screen"
zt "move the current line to screen top"
zb "move the current line to bottom screen"
ZZ "equal to :wq<CR> or :x<CR>"
ZQ "equal to :q!<CR>"
^g "show where you current are"
^o "go back to the next position"
^i "go forward to the next position"
o "open a new line and start insert"
O "open a new line above and start insert"
:wq "write and quit the current window"
de "from the cursor, delete to the end space without space"
dw "from the cursor, delete to the end space and space"
u "undo"
^R "redo"
. "VERY IMPORTANT. repeat last operation"
d$ "delete to the end of the line"
2w "two words forward"
3e "to the end of the 3rd word forward"
0 "move to the start of the line"
/xxxx "search xxxx"
w & d2w "move cursor, and delete 2 words"
2dd "delete 2 lines"
U "undo changes in the whole line"
r[x] "replace a character with [x]"
<num>s "delete s character and go to insert mode"
ce "change the word until the end"
cc "change the whole line, NOT until the end"
c$ "change the line until the end"
cw "change the word, seems equal to ce"
ciw "change in word, all word, not from the cursor"
xxG "move to line xx"
:xx "move to line xx"
n "next search"
N "backward search"
?xxxx "backward search xxxx"
% "find a matching bracket"
:s/thee/the "replace the first thee with the within one line"
:s/thee/the/g "replace, globally in the line"
:s/thee/the/gc "replace globally, but ask you to decide"
:%s/old/new/g "CAREFUL! change every occurrence inthe whole file"
:#,#s/old/new/g "#,# are the line numbers"
:! "execute an external command. Example: #!ls<Enter>"
:w filename "write to file filename"
v "start visual mode"
V "select the whole line"
^V "start block select v mode"
:r FILENAME "VERY IMPORTANT: insert the contents of a file"
:r !command "VERY IMPORTANT: read the output of an external command and insert"
a "insert after the cursor. i is insert befort the cursor."
R "continue replace a lot of characters"
y "copy text"
yw "copy one word"
yy "copy the whole line"
set ic "ignore case when search"
set hls is"high light search and incremental search"
set noic nohls nois "disable ic hls is"
:help command "getting help"
:q "quit help"
^W^W "jump from one window to another"
F1 "start help"
:help w
:help c_CTRL-D
:help insert-index
:help user-manual
:e^D "^D means command line completion. you can also use <TAB>"
set nocp "make sure vim is not in compatible mode"
<sym>=b() [] B{} <> '' ""
ci<sym> "change in <sym>"
di<sym> "delete in <sym>"
yi<sym> "copy in <sym>"
vi<sym> "select in <sym>"
ca<sym> "change include <sym>"
da<sym> "delete include <sym>"
ya<sym> "copy include <sym>"
va<sym> "selet include <sym>"
^ "move the cursor to the first NOT blank character"
:n "edit next file"
:N "edit last file"
:files "list all files opened"
:sp filename "open a newfile"
^w<hjkl> "move current window, hjkl"
qa "VERY IMPORTANT. macro recording start/stop. save to reg a"
@a "do the macro recording in reg a"
xxx@a "do the macro xxx times"
^a "number add 1"
<num>^a "number add num"
^x "number minus 1"
<num>^x "number minus num"
:g/V/t.|-d<CR>ZZ "hello vimgolf!"
<ins>^u "delete all before cursor"
<ins>^w "delete word before cursor"
<ins>^o "execute a normal command once"
<num>fx "find the num-th character x"
```
