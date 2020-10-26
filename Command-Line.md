## ***Command Line:***

* essential tool for software development.
* useful to execute a wide variety of programs on your computer.
* a tool for interacting with a computer using text (also known as a *text interface*).

***Unix Commands*** is a type of command that is used in Linux and macOS.

***Commands*** are instruction given to the computer into what is called a ***terminal***.

* NOTE: 1. For Windows we use **POWERSHELL** or **GIT BASH**.

* NOTE: 2. Here we will use the word *directory* (*plural: directories*) in place of *folder* oftenly. They both are the *same thing*, and they're used *interchangeably*.

### ***Commands:***

*  `start .` *(for windows) or* `open .` *(for linux/macOS)*
    - Opens File Explorer where we use *GUI* to manipulate the Files or Folders/Directories.

*  `pwd`
    - stands for **P**rint **W**orking **D**irectory.
    - On command line, it is important to know the directory you're working. Here comes `pwd` command to check that.
    - When you execute the `pwd` command, all the directories from the root directory to the current directory are displayed.

* `ls`
    - when moving between directories, it would be convenient if we could see the list of files and directories in the current directory. `ls` command is used for same.
    - it is important to note that `ls` command will only display the files and directoriesthat are direct children of the current directory.
    - to read hidden files give command: `ls -a`

* `cd`
    - stands for **C**hange **D**irectory.
    - if you execute `cd` without specifying a directory, you can move to what is called a ***home directory***.
    
    i. `cd directory_name` command helps you to move to other specified directory.

    ii. `cd ..` command let you move back to you previous folder.

* `mkdir directory_name`
    - you can create a new directory using `mkdir directory_name` command as well.

* `touch filename.extension`
    - you can create an empty file of any type.

* `cat filename.extension`
    - it displays the text content of the file.

* `cp file_to_copy new_file_name`
    - used for coping files.

* `cp -r directory_to_copy new_directory_name`
    - used for coping directories.
    - **-r** stands for recursive function.
    - ***important***: not applying `-r` will result to an error and the command will not be executed.

* `cp file_to_rename new_file_name`
    - used for renaming files.

*  `rm filename.extension`
    - used for deleting files.

*   `rm -r directory_name`
    - used for deleting directory which are non-empty.

*   `rmdir directory_name`
    - used for deleting directory which are empty.