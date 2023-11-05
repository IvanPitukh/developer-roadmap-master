# Text Manipulation

Some of the most common commands you will use in the terminal are text manipulation commands. These commands allow you to search, replace, and manipulate text in files and streams. Here are some of the most common commands you will use:

- `awk` - A programming language designed for text processing and typically used as a data extraction and reporting tool.
- `sed` - A stream editor for filtering and transforming text.
- `grep` - A command-line utility for searching plain-text data sets for lines that match a regular expression.
- `sort` - A command-line utility for sorting lines of text files.
- `cut` - A command-line utility for cutting sections from each line of files.
- `uniq` - A command-line utility for reporting or omitting repeated lines.
- `cat` - A command-line utility for concatenating files and printing on the standard output.
- `echo` - A command-line utility for displaying a line of text.
- `fmt` - A command-line utility for simple optimal text formatting.
- `tr` - A command-line utility for translating or deleting characters.
- `nl` - A command-line utility for numbering lines of files.
- `wc` - A command-line utility for printing newline, word, and byte counts for files.

`awk` is a general-purpose scripting language used for manipulating data or text and generating reports in the Linux world. It is mostly used for pattern scanning and processing. It searches one or more files to see if they contain lines that match the specified patterns and then performs the associated actions.

- [What is AWK? How to use it?](https://www.geeksforgeeks.org/awk-command-unixlinux-examples/)
- [How AWK works?](https://linuxize.com/post/awk-command/)
- [Linux Crash Course - awk](https://www.youtube.com/watch?v=oPEnvuj9QrI)

`sed`(**S**tream **Ed**itor) command in UNIX can perform lots of functions on file like searching, finding and replacing, insertion or deletion. By using SED you can edit files even without opening them in editors like [VI Editor](https://www.redhat.com/sysadmin/introduction-vi-editor).

- [What is SED? with examples](https://www.geeksforgeeks.org/sed-command-in-linux-unix-with-examples/)
- [Detailed Manual](https://www.gnu.org/software/sed/manual/sed.html)
- [Linux Crash Course - The sed Command](https://www.youtube.com/watch?v=nXLnx8ncZyE&t=218s)

The `grep` command (**g**lobal search for **r**egular **e**xpression and **p**rint out) searches file(s) for a particular pattern of characters, and displays all lines that contain that pattern. It can be used with other commands like `ps` making it more useful.

- [What is Grep? with examples](https://www.geeksforgeeks.org/grep-command-in-unixlinux/)
- [Detailed Manual](https://www.gnu.org/software/grep/manual/grep.html)
- [Linux Crash Course - The grep Command](https://www.youtube.com/watch?v=Tc_jntovCM0)

`sort` command is used to sort the contents of a file in a particular order. By default, it sorts a file assuming the contents are in ASCII. But it also can also be used to sort numerically by using appropriate options.

- [Sort command with examples](https://www.geeksforgeeks.org/sort-command-linuxunix-examples/)
- [Options](<https://en.wikipedia.org/wiki/Sort_(Unix)>)
- [Linux Tutorials|sort command GeeksforGeeks](https://www.youtube.com/watch?v=fEx5rnbDKO4)

The cut utility cuts out selected portions of each line (as specified by list) from each file and writes them to the standard output.

- [cut Documentation](https://man7.org/linux/man-pages/man1/cut.1.html)
- [cut Cheat Sheet](https://bencane.com/2012/10/22/cheat-sheet-cutting-text-with-cut/)

The uniq utility reads the specified input_file comparing adjacent lines, and writes a copy of each unique input line to the output_file.

- [uniq Documentation](https://man7.org/linux/man-pages/man1/uniq.1.html)
- [uniq Cheat Sheet](https://www.geeksforgeeks.org/uniq-command-in-linux-with-examples/)

`cat` (concatenate) command is very frequently used in Linux. It reads data from the file and gives its content as output. It helps us to create, view, and concatenate files.

- [Cat Command with examples](https://www.tecmint.com/13-basic-cat-command-examples-in-linux/)
- [Options](<https://en.wikipedia.org/wiki/Cat_(Unix)>)
- [Linux Tutorials|cat command|GeeksforGeeks](https://www.youtube.com/watch?v=exj5WMUJ11g)

`echo` is a built-in command in Linux used to display lines of text/string that are passed as an argument. It is mostly used in shell scripts and batch files to output status text or `ENV` variables to the screen or a file.

- [Echo command with Examples](https://www.tecmint.com/echo-command-in-linux/)
- [Linux Crash Course - The echo Command](https://www.youtube.com/watch?v=S_ySzMHxMjw)

`fmt` command is for formatting and optimizing contents in text files. It will be really useful when it comes to beautify large text files by setting uniform column width and spaces.

- [Fmt command with Examples](https://www.devopsroles.com/fmt-command-in-linux-with-example/)

The tr utility copies the standard input to the standard output with substitution or deletion of selected characters.

- [tr Documentation](https://linuxcommand.org/lc3_man_pages/tr1.html)
- [tr Cheat Sheet](https://linuxopsys.com/topics/tr-command-in-linux)

The nl utility reads lines from the named file or the standard input if the file argument is omitted, applies a configurable line numbering filter operation and writes the result to the standard output.

- [nl Documentation](https://man7.org/linux/man-pages/man1/nl.1.html)
- [nl Cheat Sheet](https://www.geeksforgeeks.org/nl-command-in-linux-with-examples/)

The wc utility displays the number of lines, words, and bytes contained in each input file, or standard input (if no file is specified) to the standard output.

- [wc Documentation](https://linux.die.net/man/1/wc)
- [wc Cheat Sheet](https://onecompiler.com/cheatsheets/wc)
