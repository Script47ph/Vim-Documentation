# My Vim documentation

## Vim Keybindings

| Key           | Command                            |
| ------------- | ---------------------------------- |
| [ ESC ]       | Exit from insert mode              |
| [ i ]         | Insert mode                        |
| [ a ]         | Append mode                        |
| [ Shift + a ] | Append mode in the end of the line |
| [ x ]         | Delete character                   |
| [ dd ]        | Delete line                        |
| [ h ]         | Move left                          |
| [ j ]         | Move down                          |
| [ k ]         | Move up                            |
| [ l ]         | Move right                         |
| [ gg ]        | Go to the top of the line          |
| [ G ]         | Go to the bottom of the line       |
| [ Shift + $ ] | Go to the end of the line          |
| [ Shift + ^ ] | Go to the beginning of the line    |
| [ u ]         | Undo                               |
| [ 0 ]         | Go to the beginning of the line    |
| [ v ]         | Visual mode                        |
| [ y ]         | Yank line                          |
| [ p ]         | Paste line                         |
| [ Shift + p ] | Paste line in the end of the line  |
| [ o ]         | Insert mode with new line          |
| [ Ctrl + w ]  | Delete word in insert mod          |
| [ dw ]        | Delete word                        | 



## Vim Commands

<!-- <div align="center"> -->

| Key           | Command             |
| ------------- | ------------------- |
| :w            | Save                |
| :q            | Quit                |
| :q!           | Quit without saving |
| :wq           | Save and quit       |
| :w <filename> | Save as <filename>  |
| :r <filename> | Read <filename>     |
| :! <command>  | Run <command>       |
| :e <filename> | Edit <filename>     |
| :bp           | Breakpoint          |
| :bn           | Next breakpoint     |
| :bd           | Delete breakpoint   |
| :split <filename> | Split <filename> |
| :vsplit or :vs <filename> | Vertical Split <filename> |




<!-- </div> -->

## Vim tips and tricks

- Minimize opened vim with [Ctrl + z] and check the process list with commands `jobs`
- Re-open vim with commands `fg`
- To re-open specific vim if multiple vim are minimized, use `fg N`. The N is job number and can be seen in the `jobs` list.

  Note: on zsh, use `fg %N` instead of `fg N`.
