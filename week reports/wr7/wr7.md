```
    name: sahil v patel
    course: cis 106
    semester: spring 23
```

# WEEK REPORT 7: 

## Cat Command

Cat Command is used for displaying content of a file.
```formula: cat -n ~/Downloads/filename.txt```
```Examples: cat -n ~/Documents/todo.lst, cat -n ~/Documents/todo.md```

## tac command

tac command is used for displaying the content of a file in reverse order*
```formula: tac + option _ files to display```
```EXAMPLE :tac todo.md, tac ~/Documents/todo.md```

## head command

the head command displays the top N number of lines in a given file.
```formula: head + options + files```
```examples: head ~/Documents/book/dracula.txt, head -5 ~/Documents/book/dracula.txt```

## tail command

tail command displays the bottom N number of lines in a given file
```formula: tail + options + files```
```examples: tail ~/Documents/book/dracula.txt, tail -5 ~/Documents/book/dracula.txt```

## cut command

cut command is used to extract a section and display the file to a screen
```formula: cut + options + files```
```examples: cut -d ':' -f1/etc/passwd, ls -l | cut -d' ' --complement -s -f1```

## paste command

paste command is used for joining files horizontally in columns
```formula: paste + options + files```
```examples: paste .users.lst ip_address.lst, paste -d ':' .users.lst```

## sort command

sort command is used for sorting files
```formula: sort + option + files```
```examples: sort users.lst, sort -o sorted.lst users.lst```

## wc command

wc command is used for printing the number of lines, characters and bytes in a file.
```formula: wc + options + files```
```examples: wc -m users.txt, wc -w users.txt```

## tr command

tr command is used for translating or deleting characters from standard output
formula: tr + option + set + set
examples: cat file.txt | tr '_' ',' cat file.py | tr "[:space:]" ' '

## diff command

diff command compares files and displays the differences between them
```formula: diff + option + file1 + file2```
```examples: diff cars.csv cars-backup.csv, diff -y cars.csv cars-backup.csv```
## grep command
grep command is used to search text in given file. grep works line by line basis
```formula : grep + option + search criteria + files```
```Example :grep 'dracula' ~/Documents/dracula.txt```
```grep -i  'dracula' ~/Documents/dracula.txt```
## sed command

sed command is used for processing and manipulating text
```formula: sed + option + files```
```examples: sed 's/pattern/replacement/' file.txt```
``` sed 's/pizza/rice/' shopping-list.1st```
```sed 's/pizza/rice/4' shopping-list.lst```
```sed 's/pizza/rice/3g' shopping-list.lst```
```sed '3 s/pizza/rice/' shopping-list.lst```
## awk command

awk command is a versatile to process files
```formula: awk -F: '{print $1}' /etc/passwd```
```awk -F : '{print $1,$NF}' /etc/passwd```
```awk -F: '{print toupper($1)}' /etc/passwd```
```grep "bash" /etc/passwd | awk -F: 'BEGIN {printf "%s\t%s\n","User","Shell"}{print $1,"\t",$7}'```
```grep "bash" /etc/passwd | awk -F: 'BEGIN {printf "%s\t%s\n","User","Shell"}{print toupper($1),"\t",$7}'```

#FINISH
