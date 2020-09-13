# user-CLI
The program sets a platphorm just as the Shell platphorm (also known as terminal) in Linux, or shortly any user CLI.
Every Shell's expected input is commands from the user. It passes them to execution to the operating system.
Like other common Shells , our program also shows "prompt" line as following: "username@directory>". After that, the user needs to enter a command and relevant arguments (if needed, depends on the command).
In case the input is illegal (not executable, or no such command), the program will do nothing with it, show the prompt again and wait for input.
Important detail is the command cannot be more than 510 characters. No other limitations.

Basicly, our Shell supports every command the user can enter in the original Shell, and the output we would expect is changing according to the command that was entered.
The command "cd" is not supported by our Shell- when enetring that command "command not supported (Yet)" will show on the screen, and the prompt of course, waiting for the next command.
 As long the input is not "done", the program will continue execute commands, show the prompt again and wait for the next command from the user.
Moreover, also commands include pipe sign | and redirections to files such as >,<,>>,2> etc. are supported, seperatly and both together (only when the pipe appears before the redirection). as said above, the input will be exactly the same as the original Shell will show.
After "done" has been entered, there are few details printed on the screen- amount of all commands, commands that include pipe, commands that include redirection, length of all commands together and the average length of each command.
Also a greeting is shown, and the program ends.
