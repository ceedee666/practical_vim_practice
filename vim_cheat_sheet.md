# Switching modes
| Command       | Explanation           |
|---------------|-----------------------|
| `A`           | `$a` - Move to the end of the line and append |
| `o`           | `A<CR>` - Open a new line below |
| `O`           | `ko` - Open a new line above |
| `C`           | `c$` - Delete form current position to the end of the line |´
| `s`           | `cl` - Delete current char and enter insert mode |

# Searching and replacing
| Command       | Explanation           |
|---------------|-----------------------|
| `f<char>`     | Scan line for the next occurence of char |
| `F<char>`     | Scan the line for the previous char |
| `/pattern<cr>`| Scan document for the next occurence of the pattern |
| `?pattern<cr>`| Scan the document for the previous occurence of the pattern |
| `:s/target/replacement` | Substitute target with replacement |

# Repeating commands
| Command       | Explanation           |
|---------------|-----------------------|
| `.`           | Repeat previous edit |
| `;`           | Repeat previous move/find |
| `n`,`N`       | Repeat/reverse previous scan|
| `;`           | Repeat previous move |
