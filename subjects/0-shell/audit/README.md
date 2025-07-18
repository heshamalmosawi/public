#### General

###### Was the project written in Rust?

###### Are the commands mentioned in the subject implemented from scratch, without calling any external binaries?

The use of external binaries or system calls that spawn them is strictly forbidden, as the project requires implementing all functionality from scratch without relying on external programs.

#### Functional

##### Open a terminal and run the project.

###### Can you confirm that the project runs and displays a unix shell?

##### Open a terminal and run the project.

###### Can you confirm that this interpreter displays at least a simple `$` and waits for you to type a command?

##### Try to run a command of your choice.

###### Can you confirm that the interpreter only validates the command if you press enter?

##### Try to run the command `exit`.

###### Can you confirm that the interpreter terminates properly and gives back the parent's shell?

##### Try to run the command `echo "something!"`. Do the same in your computer terminal.

###### Can you confirm that the displayed message of the project is exactly the same as the computer terminal?

##### Try to run the command `echo something else` (without double quotes). Do the same in your computer terminal.

###### Can you confirm that the displayed message of the project is exactly the same as the computer terminal?

##### Try to run the command `pwd`.

###### Can you confirm that the interpreter displayed the current path?

##### Try to open the project and create a parent folder with two children folders using the command `mkdir`. Then enter the parent folder and do `pwd`.

###### Can you confirm that the interpreter displayed the current path?

##### Try to enter a directory of your choice by using the command `cd dir/of/your/choice`.

###### Can you confirm that the interpreter took you to the correct path? Use `pwd` to confirm.

##### Try to run only the command `cd`.

###### Can you confirm that the interpreter took you to the users home folder? Use `pwd` to confirm.

##### Try to run the command `ls` in a directory at your choice. Do the same in your computer terminal.

###### Can you confirm that the output is similar in the project and in your computer terminal?

##### Try to run the command `ls -l -a -F` in a directory at your choice. Do the same in your computer terminal.

###### Can you confirm that the output is similar in the project and in your computer terminal?

##### Try to run the commands `mkdir new_folder1` and `mkdir new_folder2` in a directory of your choice.

###### Can you confirm that the directories `new_folder1` and `new_folder2` were created?

##### Create a document inside the `new_folder1` called `new_doc.txt` with some random text inside. Try to run the command `cp new_doc.txt ../folder2` to copy the document to the folder `new_folder2`.

###### Can you confirm that the document `new_doc.txt` is inside the `new_folder2`?

##### Try to run the command `cat` with no arguments.

###### Can you confirm that you can type some text and see it displayed back?

###### Can you confirm that you can stop with `Ctrl+D`?  

##### Try to run the command `cat new_folder1/new_doc`. Do the same in your computer terminal.

###### Can you confirm that the output is the same in the project and in your computer terminal?

##### Try to run the commands `mv new_folder2 new_folder1` to move the directory `new_folder2` inside of the directory `new_folder1`.

###### Can you confirm that the directory `new_folder2` is inside of the directory `new_folder1`?

##### Try to run the command `rm -r new_folder1` to remove what was created above.

###### Can you confirm that the directory `new_folder1` was removed?

#### Bonus

###### +Did the student handle `Ctrl + C` gracefully?

###### +Did the student add auto-completion when writing a command?

###### +Did the student implement command history?

###### +Did the student implement commaing chaining with `;`?

###### +Did the student implement piping?

###### +Did the student add colors to the errors or directories?

###### +Did the student implement redirection?

###### +Did the student display the current directory in the prompt?

###### +Did the student add any other features or commands to the project?

###### +Did the student implement a custom `help` command documenting functionality?

###### +Did the student implement support for environment variables?
