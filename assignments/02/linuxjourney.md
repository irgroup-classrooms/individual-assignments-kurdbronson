# Command Line - Exercises
### 1. The Shell
Q: What should be outputted to the display when you type echo Hello World?
  - _Hello World_

E: Try some other Linux commands and see what they output:
-  _:$ date_ = gives me the current Date
-  _:$ whoami_ = tells me how is the current user 
### 2. pwd(Print Working Directory)
Q:How do I find what directory you are currently in?
- _:$ pdw_

### 3. cd (Change Directory)
E:Run the cd command without any flags, where does it take you?
- _to the root directory_
  
Q: If you are in /home/pete/Pictures and wanted to go to /home/pete, what’s a good shortcut to use?
- _$:cd .._

### 4. ls (List Directories)
E: Run ls with different flags and see the output you receive.

- _$:ls -R (recursively list directory contents)_
- _$:ls -r (reverse order while sorting)_
- _$:ls -t (sort by modification time, newest first)_

Q: What command would you use to see hidden files?
- _$:ls -a_
### 5. touch
E:  
- Create a new file _$:touch_
- Note the timestamp
- Touch the file and check the timestamp once again
  
Q: How do you create a file called myfile?
- _$:touch myfile_

### 6. file
E: Run the file command on a few different directories and files and note the output.
- $:file THDB_Blatt.pdf  = THDB_Blatt.pdf: PDF document, version 1.7, 1 page(s)
- $:file DIS13_Notizen.docx = DIS13_Notizen.docx: Microsoft Word 2007+

Q: What command can you use to find the file type of a file?
- $:file

### 7. cat
E: Run cat on different files and directories. Then try to cat multiple files. 
- _$:cat shell_kurzbefehle.txt (gives me a view into the file)_
- _$:cat Shell_Kurzbefehle.txt TheShell_Tutorial.txt (gives me a view to both files)_

Q: What's a good way to see the contents of a file?
- _$:cat myfile_

### 8. less
E: Run less on a file, then page up and around the file. Try searching for a specific word. Quickly navigate to the beginning or the end of the file.
- _q - Used to quit out of less and go back to your shell._

- _Page up, Page down, Up and Down - Navigate using the arrow keys and page keys._

- _g - Moves to beginning of the text file._

- _G - Moves to the end of the text file._

- _/search - You can search for specific text inside the text document. Prefacing the words you want to search with /_

- _h - If you need a little help about how to use less while you’re in less, use help._


Q: How do you quit out of a less command?
- press _q_ on the _keyboard_

###9
### 9. history
E: Navigate through your previous command history with the Up and Down keys. Play around with ctrl-R reverse search.
- _$:history (I can view my previous commands.)_
  
- by pressing _ctrl_R_ I can search previous command in my commandline

Q: What is the command to clear the terminal?

- _$:clear_


### 10. cp(Copy)

E: Copy over a couple of files, be careful not to overwrite anything important.
with _$: *.txt /desktop/uni/dis11_ I copied several textdocuments to a different directory.

Q: What flag do you need to specify to copy over a directory?
- _$:cp - i_

### 11. mv(Move)

E: Rename a file, then move that file to a different directory.
- _$: mv oldfile newfile_
- _$: mv file2 /home/pete/Documents_

Q: How do you rename a file called cat to dog?
- _$:mv cat dog_

### 12. mkdir (Make Directory)

E: Make a couple of directories and move some files into that directory.
- _$: mkdir books paintings_
- _$: mv file1 file2 /books_

Q: What command is use to make a directory?
- _$:mkdir_

### 13. rm (Remove)

E: Create a file called -file (don't forget the dash!).
   Remove that file.
- _$: touch -file_
- _$: rm -file_

Q: How do you remove a file called myfile? 
- _$:rm myfile_

### 14. find

E: Find a file from the root directory that has the word net in it.
- _$: find -name net_

Q: What option should I specify for find if I want to search by name?  
- _$: find -name_

### 15. find

E: Run help on the echo command, logout command and pwd command.
- _$: help echo_

Q: How do you get quick command line help for built-in bash commands?  
- _$: help_

### 16. man

E: Run the man command on the ls command.
- _$: man ls_

Q: How do you see the manuals for a command?  
- _$: man_

### 17. whatis

E: Run the whatis command on the less command.
- _$: whatis less_

Q: What command can you use to see a small description of a command?  
- _$: whatis_

### 18. alias

E: Create a couple of aliases then remove them.
- _$: alias foobar='ls -la'_

Q: What command is used to make an alias?  
- _$: alias_

### 19. exit

E: Exit out of the shell and see what happens. Make sure you don't need to do anymore work in that shell.
- _$: exit_

Q: How can you exit from the shell?   
- _$: exit_










    
