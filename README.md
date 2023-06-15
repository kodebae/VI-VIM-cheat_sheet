# VI-VIM-cheat_sheet
VI / VIM Cheat Sheet

## Intro
VI (pronounced "vee-eye") and Vim (short for "Vi IMproved") are text editors commonly used in Unix and Unix-like systems. They are known for their powerful editing capabilities and are particularly popular among programmers, system administrators, and power users.

VI is the original text editor that was created in the 1970s as part of the Unix operating system. It is a command-line-based editor and is available on almost all Unix-like systems, including Linux and macOS. Vim, on the other hand, is a more advanced version of VI that was developed in the early 1990s and includes additional features and improvements.

Both VI and Vim are modal editors, which means they have different modes for editing and navigating through text.

Vim offers numerous features that make it a powerful text editor, including syntax highlighting, code folding, powerful search and replace capabilities, support for plugins, customizable keybindings, and many more. It is highly configurable and can be extended to suit individual needs.

Despite having a steep learning curve, VI/Vim is appreciated by many users for its efficiency and productivity once mastered. It is often preferred for editing configuration files, writing code, and performing various text manipulation tasks from the command line.
________________________________________________
> Vim Documentation -> [click here to go to docs](https://www.vim.org/docs.php)

<strong>Vim works in modes, in normal mode/command mode keys have normal functionalities.</strong>

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
- set relative number
```
:set <space> relativenumber
```
- use numbers to navigate files
```
5 + <arrow right key> 'moves cursor 5 places to the left'
10 + <arrow down key> 'moves cursor down 10 lines`
substitute for the h, j, k, l keys instead of arrow keys
```



### Mode Information

Vim has several modes, each serving a specific purpose. The main modes in Vim are:

1. Normal mode (also known as Command mode): This is the default mode when you launch Vim. In this mode, you can navigate through the file, issue commands, and perform operations such as copying, pasting, deleting, and searching. You can switch to normal mode from other modes by pressing the Esc key.

2. Insert mode: In this mode, you can directly type and insert text into the file. To enter insert mode from normal mode, press the "i" key. There are other commands to switch to insert mode from normal mode, such as "a" (append after the cursor), "I" (insert at the beginning of the line), and more.

3. Visual mode: This mode allows you to visually select blocks of text for editing, copying, or deleting. You can enter visual mode from normal mode by pressing the "v" key. There are also other variants of visual mode, such as "V" (line-wise visual mode) and Ctrl+v (block-wise visual mode).

4. Command-line mode: This mode is used for entering Ex commands, which are more advanced commands for tasks such as saving files, searching, replacing, and running external commands. You can enter command-line mode by pressing ":" in normal mode. The command-line mode is indicated at the bottom of the Vim window.

In addition to these main modes, Vim also has several sub-modes and specialized modes, including:

- Replace mode: This mode allows you to overwrite text as you type. You can enter replace mode from normal mode by pressing the "R" key.

- Visual block mode: This mode is an extension of visual mode that allows you to select a block of text in a rectangular shape. You can enter visual block mode by pressing Ctrl+v in visual mode.

- Select mode: This mode is similar to visual mode, but it's more interactive and enables features like selection with mouse support. You can enter select mode by pressing "g" and then "v" in normal mode.

These are some of the most commonly used modes in Vim. Each mode provides different functionality and allows you to perform specific operations efficiently.