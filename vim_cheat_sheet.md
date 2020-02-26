# Text objects
| Command       | Explanation           |
|---------------|-----------------------|
| `l`           | a single char         |
| `aw`          | a word                |
| `ap`          | a paragraph           |



# Operators
Some important rules on operators:
- Repeating an operator works on a whole line. E.g. `yy` copys the whole line.

| Command       | Explanation             |
|---------------|-------------------------|
| `c`           | change                  |
| `d`           | delete                  |
| `y`           | yank (copy)             |
| `[c]yy`       | copy [c] number of line |
| `g~`          | Swap case               |
| `gu`          | Make lowercase          |
| `gU`          | Make uppercase          |
| `>`           | Shift rigth             |
| `<`           | Shift left              |
| `=`           | Autoindent              |


# Searching and replacing
| Command       | Explanation           |
|---------------|-----------------------|
| `f<char>`               | scan line for the next occurence of char |
| `F<char>`               | scan the line for the previous char |
| `/pattern<cr>`          | scan document for the next occurence of the pattern |
| `?pattern<cr>`          | scan the document for the previous occurence of the pattern |
| `:s/target/replacement` | Substitute target with replacement |
| `*`                     | Search the word under the cursor |


# Repeating commands
| Command       | Explanation           |
|---------------|-----------------------|
| `.`           | Repeat previous edit |
| `;`           | Repeat previous move/find |
| `n`,`N`       | Repeat/reverse previous scan|



#Modes

## Switching modes
| Command       | Explanation                                               |
|---------------|-----------------------------------------------------------|
| `A`           | `$a` - Move to the end of the line and append             |
| `o`           | `A<CR>` - Open a new line below                           |
| `O`           | `ko` - Open a new line above                              |
| `C`           | `c$` - Delete form current position to the end of the line| 
| `s`           | `cl` - Delete current char and enter insert mode          |
| 'R'           | Enter replace mode                                        |


## Insert Mode
| Command       | Explanation                  |
|---------------|------------------------------|
| `<C-h>`       | delete back one char         | 
| `<C-w>`       | delete back one word         |
| `<C-u>`       | delete back to start of line |


## Visual Mode
| Command       | Explanation           |
|---------------|-----------------------|
| `v`           | character-wise visual mode|
| `V`           | line-wise visual mode|
| `<C-v>`       | block-wise visual mode|
| `gv`          | reselect last selection|
| `o`           | go to other end of selected text |


# Windows, Tabs and Buffers

## Multiple Buffers
| Command            | Explanation          |
|--------------------|----------------------|
| :ls                | Show list of open bufffers |
| :buffer N (:b N)   | Jump to buffer N | 
| :bn           | Next bufffer         |
| :bp           | previous buffer      |

## Multiple Windows
| Command       | Explanation          |
|---------------|----------------------|
| `:sp[lit] {file}     | Split window horizontally, load file in new window |
| `:vsp[lit] {file}    | Split window vertically, load file in new window |
| `<C-w>s`             | Split windows horizontally |
| `<C-w>v`             | Split windows vertically |
| `<C-w>w`             | Cycle between windows |
| `<C-w>q`             | Quit a window |
| `<C-w>c` or :cl[ose] | Close active window |
| `<C-w>o` or :on[ly]  | Close other windows, keep only active window |



## Multiple Tabs
| Command       | Explanation          |
|---------------|----------------------|
| :tabe[dit]    | Make a new tab       |
| `gt`          | Go to the next tab   |
| `gT`          | Go to the previous tab |
| `<C-w>T`      | Move currentz window into new tab |


# Misc
| Command       | Explanation          |
|---------------|----------------------|
| `<C-a>`       | add on a number      |
| `<C-x>`       | sub on a number      |
| `zz`          | redraw screen with current line in center |
| `<C-r>=`      | enter the expression register (to perform calulations) |
