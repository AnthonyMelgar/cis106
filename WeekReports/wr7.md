--- 
Name: Anthony Melgar
Course: cis106
Semester: Fall 23
---

# Week Report 7

## Handling Text Files

### cat command
**What is the command used for?**
Command is used for displaying the content of a file.
**What is the formula of the command?**
` cat + option + files to display`
**2 examples of using the command**
`cat -n ~/Documents/cars.md`
`cat -b ~/Documents/movies.md`

### tac command
**What is the command used for?**
Command is used for displaying the content of a file in reverse order.
**What is the formula of the command?**
`tac + option + files to display`
**2 examples of using the command**
`tac games.md`
`tac ~/Documents/apps.md`

### head command
**What is the command used for?**
Command displays the top N number of line. Prints the first 10 lines.
**What is the formula of the command?**
`head + option + files`
**2 examples of using the command**
`head ~/Documents/book/bible.txt`
`head -3 ~/Documents/book/bible.txt`

### tail command
**What is the command used for?**
Command displays the last N number of line. Prints the last 10 lines.
**What is the formula of the command?**
`tail + option + file`
**2 examples of using the command**
`tail ~/Documents/book/history.txt`
`tail -4 ~/Documents/book/history.txt`

### cut command
**What is the command used for?**
Command used to extract a specific section of each line of a file and display it.
**What is the formula of the command?**
`cut + option + files`
**2 examples of using the command**
`cut -d ':' f1 /etc/passwd`
`cut -d ':' -f1,5 /etc/passwd`

### paste command 
**What is the command used for?**
Command used for joining files horizontally in a columns.
**What is the formula of the command?**
`paste + option + files`
**2 examples of using the command**
`paste users.lst social_number.lst`
`paste -d ":" users2.lst social_number.lst`

### sort command
**What is the command used for?**
Command used for sorting files by alphabetically in reverse order by number and by month.
**What is the formula of the command?**
`sort + option + file`
**2 examples of using the command**
`sort -o sorted.lst users.lst`
`sort -k 4 users.txt`

### wc command 
**What is the command used for?**
Command used for printing the number of lines characters and bytes in a file.
**What is the formula of the command?**
`wc + option + files`
**2 examples of using the command**
`wc -m michael.txt`
`wc -w michael.txt`

### tr command
**What is the command used for?**
Command used for translating or deleting characters from standard output.
**What is the formula of the command?**
`Standard output | tr + option + set + set`
**2 examples of using the command**
`cat program.py | tr "[:space:]" '/t'`
`cat file.py | tr -s "[:space:]" '/t'`

### diff command 
**What is the command used for?**
Command used for compares files and displays the differences between them.
**What is the formula of the command?**
`diff + option + file1 + file2`
**2 examples of using the command**
`diff movies.mov movies-backup.mov`
`diff -y music.mp4 music-backup.mp4`

### grep command
**What is the command used for?**
Command used for search text in given files.
**What is the formula of the command?**
`grep + option + search criteria + file`
**2 examples of using the command**
`grep 'halloween' ~/Documents/halloween.txt`
`grep -i 'halloween' ~Documents/halloween.txt`

### awk command
**What is the command used for?**
Command used for processing and displaying text.
**What is the formula of the command?**
`awk + option + {awk command} + file + file to save` 
**5 examples of using the command**
`awk '{print $3}' ~Documents/mp3/songs.mp3`
`awk 'NR > 4 { print }' /etc/passwd`
`awk -F '{print $NF}' /etc/passwd`
`awk -F '{print NR,$2,5} /etc/passwd`
`awk -F '{print toupper($7)}' /etc/passwd`

### sed command
**What is the command used for?**
Command used for a stream editor the performs operations on files and standard output.
**What is the formula of the command?**
`sed option + sed script + file`
**5 examples of using the command**
`sed 's/cereal/chip/5' shopping-list.lst`
`sed 's/fruits/oatmeal/g' shopping-list.lst`
`sed '3 s/meat/chicken/' shopping-list.lst`
`sed '1,3 s/fish/cake/' shopping-list.lst`
`sed '5d' shopping-list.lst`
