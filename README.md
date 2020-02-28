# myvim
My Vim configuration

# Memory Aid

(From Danielmissler)[https://danielmiessler.com/study/vim/]


## VERBS
```
d: delete  
c: change. 
y: yank (copy). 
v: visually select (V for line vs. character) 
```
## NOUNS
```
w: word
s: sentence
): sentence (another way of doing it)
p: paragraph
}: paragraph (another way of doing it)
t: tag (think HTML/XML)
b: block (think programming)
```

## MOVING
```
j: move down one line
k: move up one line
h: move left one character
l: move right one character
0: move to the beginning of the line
$: move to the end of the line
w: move forward one word
b: move back one word
e: move to the end of your word
): move forward one sentence
}: move forward one paragraph
:line_number: move to a given line number
H: move to the top of the screen
M: move to the middle of the screen
L: move to the bottom of the screen
^E: scroll up one line
^Y: scroll down one line
gg: go to the top of the file
G: go to the bottom of the file
^U: move up half a page
^D: move down half a page
^F: move down a page
^B: move up a page
Ctrl-i: jump to your previous navigation location
Ctrl-o: jump back to where you were

```
## START

>> Let's recall our language: Verb, Modifier, Noun. So we're assuming we're starting in Normal Mode, and we're going to switch into Insert Mode in order to change something.

```
insert
i: insert before the cursor
a: append after the cursor
I: insert at the beginning of the line
A: append at the end of the line
o: open a new line below the current one
O: open a new line above the current one
r: replace the one character under your cursor
R: replace the character under your cursor, but just keep typing afterwards
cm: change whatever you define as a movement, e.g. a word, or a sentence, or a paragraph.
C: change the current line from where you're at
ct?: change change up to the question mark
s: substitute from where you are to the next command (noun)
S: substitute the entire current line


deletion
x: exterminate (delete) the character under the cursor
X: exterminate (delete) the character before the cursor
dm: delete whatever you define as a movement, e.g. a word, or a sentence, or a paragraph.
dd: delete the current line
dt.: delete delete from where you are to the period
D: delete to the end of the line
J: join the current line with the next one (delete what's between)

copy/paste
y: yank (copy) from where you are to the next command (noun)
yy: a shortcut for copying the current line
p: paste the copied (or deleted) text after the current cursor position
P: paste the copied (or deleted) text before the current cursor position


```

## SPELL
```
set spell spelllang=en_us

- Go to the next missplled word
]s 
- Go to the last misspelled word
[s

- Get suggestions
zg

```



