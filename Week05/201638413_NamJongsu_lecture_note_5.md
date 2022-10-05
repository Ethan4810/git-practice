# Week 05: Lecture Note

## **I/O Redirection: Standard Output**

**>**: Redirect output using ">" after a command to create and save the output in a file.

```sh
$ ls -lh > file_list.txt
```

---

**cat**: Displays the content of a text file.

```sh
$ cat file_list.txt
```

---

**>>**: Appends output to an existing file if it already exists, or create and write to a new file it it doesn't.

```sh
$ ls -lh >> file_list.txt
```

---

**<**: Redirect input from a file.

```sh
$ sort < words.txt > sorted_words.txt
```

---

**|**: Pipeline feeds output of previous command to input of next command. press "q" key to exit the screen.

```sh
$ ls -lh | less
```

---

**echo**: Displays line of text or string that are passed as an argument.

- echo "text" : Displays a text or a string.

```sh
$ echo print out the text
```

- echo \* : Prints all files/folders, similar to "ls".command

```sh
$ echo *
```

- echo ~ : Denotes a user's home directory.

```sh
$ echo ~
```

---

## **Permissions**

**chmod**: Changes permissions.

```sh
$ chmod 600 some_file
```

---

**sudo**: A superuser has all system administration authority. Put "sudo" before the command if you are a superuser.

```sh
$ sudo -i
```

---

## **Tips**

**\\**: Backslash can be used to ignore line change in command to enter a long command in multiple lines.

```sh
$ ls -l \
> --reverse \
> --human-readable
```

---

**history**: Type "history" to see previous command history, or save it to a text file.

```sh
$ history history_command.txt
$ cat history_command.txt
```

---
