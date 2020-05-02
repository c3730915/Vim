#  VIM usages



## text objects

- w -words
- s -sentences
- p -paragraphs
- t -tags

## Motions

- a -all
- i -in
- t -till
- f -find forward
- F -find backward

## Commands
- d -delete(also cut)

- c -change(delete and place in insert mode)

- y -yank(copy)

- v -visually select

- e -to the end of the word

- b -to the beginning of the word

- . -repeate last command

  --------------------------------





**{Command}{text object or motion}**

- diw -delete in word
- caw -change all word
- ciw -change in word
- ct) -change to ), deletes all in the () and insert
- yi) yank all text inside parentheses
- di) delete all text inside parentheses
- va" -visually select all inside doublequotes, including doublequotes
- vt" -same thing, but not including doublequotes
- fs -jump to "s" character, + ; to the next result



## Position


|  vi command   |                         description                          |
| :-----------: | :----------------------------------------------------------: |
|       0       |            move to beginning of the current line             |
|       $       |                     move to end of line                      |
|       H       |         move to the top of the current window (high)         |
|       M       |      move to the middle of the current window (middle)       |
|       L       |     move to the bottom line of the current window (low)      |
|       A       |                To the end of line and insert                 |
|       O       |              insert a new line below and insert              |
|      20G      |              move to the 20th line of the file               |
|       G       |              move to the last line of the file               |
|      gg       |              move to the first line of the file              |
|      w&b      |                   the next &previous word                    |
| :%s/foo/bar/g | Find each occurrence of 'foo' (in all lines), and replace it with 'bar'.(%means global) |
|       n       | When you're searching something, press esc and n to the next result |

## Operation

- X to delete something, but it's back forward . 
- U to undo

  

|  vi command  |                    description                    |
| :----------: | :-----------------------------------------------: |
| v, V, Ctrl+v |        Character mode,Line mode,Block mode        |
|  u, Ctrl+r   |                   undo and redo                   |
|      r       |              replace selected block               |
|      dd      |                 to delete a line                  |
|      dw      |                    delete word                    |
|      dG      |             deletes rest of text(all)             |
|    y, yy     |            copy, copy the current line            |
|      p       |                       paste                       |
|     n, N     | when you are searching, n to the next, N forwards |
|    u, ^+r    |                   undo and redo                   |





## Page operation

| Keys |               description                |
| :--: | :--------------------------------------: |
|  ^E  |          scroll the window down          |
|  ^Y  |           scroll the window up           |
|  ^B  |            scroll up one page            |
|  H   | move the cursor to the top of the window |
|  M   | move cursor to the middle of thw window  |
|  L   | move cursor to the bottom of the window  |
|  gg  |          go to the top of file           |


#Hi
