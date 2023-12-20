```
   NAME : SAHIL V PATEL
   COURSE : CIS 106
   DATE : 12/11/23
```

## What is VIM
Vim is a highly configurable and powerful text editor that is an enhanced version of the original Unix-based Vi text editor. It is widely used on Unix and Linux systems and is known for its efficiency and versatility. Vim operates in different modes, allowing users to navigate, edit, and manipulate text with various commands.

## What is nano ?
Nano is a simple and user-friendly text editor for Unix and Linux systems. It is designed to be easy for beginners and provides a straightforward interface for text editing.

## Describe in you own words how to:
Starting and Quitting Vim

### Start Vim:

**Open a terminal window.**
**Type vim followed by the filename you want to edit (e.g., vim filename.txt).**
**Press Enter.**

### Quit Vim:

**Press Esc to enter the command mode.**
**Type one of the following commands:**
        `:q` to quit without saving (if you haven't made any changes).
        `:wq` to save your changes and quit.
        `:q!` to quit without saving (even if you've made changes).
**Press Enter.**

## Vim Modes

### Vim has three main modes:

Normal mode: Used for cursor movement, text deletion, and entering commands.
Insert mode: Used for typing and editing text.
Command mode: Used for entering commands, such as saving, quitting, and searching.

## To switch modes:

    Press Esc to enter normal mode.
    Press `i` to enter insert mode.
    Press `:` to enter command mode.

## Insert Text in Vim

    Enter insert mode by pressing i.
    Type your text.
    Press Esc to return to normal mode.

## Save a File in Vim

    Enter command mode by pressing :.
    Type w and press Enter. This will save the file without changing the filename.
    Alternatively, you can type wq and press Enter to save the file and quit Vim.

## Search for a Word in Vim

    Enter command mode by pressing :.
    Type s/word/replacement/g and press Enter. This will replace all occurrences of "word" with "replacement" in the file.
    You can also use the / command to search for a specific word. For example, to search for "word," type /word and press Enter.

## Delete Text in Vim in Linux

There are several ways to delete text in Vim:

    Delete single characters:
        Press `x` to delete the character under the cursor.
        Press `dd` to delete the current line.
        Press `d$` to delete from the cursor to the end of the line.
        Press `d^` to delete from the cursor to the beginning of the line.
    Delete blocks of text:
        Press `Shift + v` to enter visual mode.
        Move the cursor to highlight the desired text block.
        Press `d` to delete the selected text.

## FINISH.