```
    name: sahil v patel
    course: cis 106
    semester: spring 23
```

## FINAL ASSIGNMENT
## QUESTION 1

| Command          | Description               | Formula/Syntax                         | Examples                                                                 |
|------------------|---------------------------|----------------------------------------|--------------------------------------------------------------------------|
| `awk`            | Powerful text processing  | `awk 'pattern {action}' filename`      | - Extract columns, calculate averages, replace text                      |
| `cat`            | Concatenate files         | `cat filename1 filename2`              | - Combine files, send file to program                                    |
| `cp`             | Copy files/directories    | `cp source destination`                | - Copy file, copy directory with contents, copy multiple files           |
| `cut`       | Extract fields from files | `cut -d delimiter [field_numbers] filename` | - Extract columns from CSV, cut specific characters, find matching lines |
| `grep`           | Search for patterns       | `grep 'pattern' filename`              | - Find lines with keywords, use regular expressions, show line numbers   |
| `head`           | View file beginnings      | `head [-n number] filename`            | - Show first 10 lines, print first line only, preview large files        |
| `ls`             | List directory contents   | `ls [options]`                         | - Show files/folders, detailed information, hidden files                 |
| `man`            | Read command manuals      | `man command_name`                     | - Get help for specific commands, search manual pages                    |
| `mkdir`          | Create directories        | `mkdir directory_name`                 | - Make new directory, create parent directories automatically            |
| `mv`             |Move/rename files/directories| `mv source destination`              | - Move file, rename file, move directory                                 |
| `tac`            | Print file lines in reverse | `tac filename`                       | - Reverse a file's content                                               |
| `tail`           | View file endings         | `tail [-n number] filename`            | - Show last 10 lines, follow log file updates                            |
| `touch`          | Create empty files        | `touch filename`                       | - Make new files quickly                                                 |
| `tr`             | Translate/substitute characters | `tr 'from' 'to' filename`        |Replace characters, uppercase/lowercase text, remove unwanted characters  |
| `tree`           | Display directory structure | `tree [directory]`                   | - Show directory hierarchy, visualize folder organization                |

## QUESTION 2
# 1)Handling Multiple Terminals:

    Open new terminals: Right-click the terminal window and choose "Open in New Tab" or "New Terminal."
    Switch between terminals: Use keyboard shortcuts like Ctrl+Tab or Alt+Tab on most systems.
    Organize terminals: Tile them side-by-side or stack them vertically for better viewing.

# 2)Mastering Manual Pages:

    Access a manual page: Use man command_name. Example: man ls for the ls command.
    Navigate the manual: Scroll with arrow keys or Page Up/Down. Use n for next page and p for previous.
    Search the manual: Type /keyword to search for a specific term within the manual page.

# 3)Redirecting Output:

    Output to a file: Use > to overwrite or >> to append the output to a file. Example: ls > file_list.txt
    Pipe output to another command: Use | to send the output of one command as input to another. Example: ls | grep "txt"

# 4)Appending and Wildcards:

    Append to a file: Use >> after the command. Example: ls >> file_list.txt to add new entries without deleting existing ones.
    Wildcards: Use * for any characters and ? for a single character. Example: cp *.txt backup/ copies all text files.

# 5)Batch Operations:

    Copy/move multiple files: Use wildcards or space-separated names. Example: cp file1.txt file2.txt backup/ or mv *.* new_folder/.
    Brace expansion: Group files with braces {start..end} or {pattern}. Example: mv file{1..5} new_folder/ moves files 1 to 5.

# 6)Building Directory Structures:

    Create multiple directories with one command: Use mkdir. 
    Example: mkdir -p project/data/logs creates the entire "project/data/logs" path if it doesn't exist.


# FINISH