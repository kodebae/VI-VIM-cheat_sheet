# VI-VIM-cheat_sheet
VI / VIM Cheat Sheet

## Intro
________________________________________________
> Vim Documentation -> [click here to go to docs](https://www.vim.org/docs.php)

<strong>Vim works in modes, in normal modes keys have normal functionalities.</strong>

### Basic Vim Key Bindings

- insert mode
```
i - insert, before cursor
I - insert at the beginning of the curr line
a - append, append after the cursor
A - append at the end of the curr line
o - open a new line right below the curr line
O - open a new line right above the curr line 
```

- exit insert mode
```
<esc>
```
- how to get out of vim
```
:q + <Enter>
```
- quit and dismiss all changes
```
:q! + <Enter>
```
- write changes
```
:w + <Enter>
```
- write and quit
```
:wq + <Enter>
```
- create line numbers
```
:set <space> number
```