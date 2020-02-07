# Text objects
| Command       | Explanation           |
|---------------|-----------------------|
| `l`           | a single char         |
| `aw`          | a word                |
| `ap`          | a paragraph           |



# Switching modes
| Command       | Explanation           |
|---------------|-----------------------|
| `A`           | `$a` - Move to the end of the line and append |
| `o`           | `A<CR>` - Open a new line below |
| `O`           | `ko` - Open a new line above |
| `C`           | `c$` - Delete form current position to the end of the line |´
| `s`           | `cl` - Delete current char and enter insert mode |


# Operators
Some important rules on operators:
- Repeating an operator works on a whole line. E.g. `yy` copys the whole line.

| Command       | Explanation           |
|---------------|-----------------------|
| `c`           | change                |
| `d`           | delete                |
| `y`           | yank (copy)           |
| `[c]yy`       | copy [c] number of line |
| `~g`          | Swap case             |
| `gu`          | Make lowercase        |
| `gU`          | Make uppercase        |
| `>`           | Shift rigth           |
| `<`           | Shift left            |
| `=`           | Autoindent            |


# Searching and replacing
| Command       | Explanation           |
|---------------|-----------------------|
| `f<char>`     | Scan line for the next occurence of char |
| `F<char>`     | Scan the line for the previous char |
| `/pattern<cr>`| Scan document for the next occurence of the pattern |
| `?pattern<cr>`| Scan the document for the previous occurence of the pattern |
| `:s/target/replacement` | Substitute target with replacement |
| `*`           | Search the word under the cursor |


# Repeating commands
| Command       | Explanation           |
|---------------|-----------------------|
| `.`           | Repeat previous edit |
| `;`           | Repeat previous move/find |
| `n`,`N`       | Repeat/reverse previous scan|
| `;`           | Repeat previous move |


# Multiple Windows
| Command       | Explanation          |
|---------------|----------------------|
| :tabe         | Make a new tab       |
| `gt`          | Go to the next tab   |
| `gT`          | Go to the previous tab |
| `vsp`         | vertically split windows |
| `ctrl+ws`     | Split windows horizontally |
| `ctrl+wv`     | Split windows vertically |
| `ctrl+ww`     | switch between windows |
| `ctrl+wq`     | Quit a window |

# Misc
| Command       | Explanation          |
|---------------|----------------------|
| `<ctrl-a>`    | add on a number      |
| `<ctrl-x>`    | sub on a number      |
