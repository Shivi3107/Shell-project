Build you custom command shell. You shell should be able to
    accept commands from the user and execute it (just the bash that we saw in
    the lab).
    
    You custom shell should be able to support the following:
    
    1.  Built-in commands: `cd`, `pwd`, `exit` (close your custom shell itself).
    
    2.  Accept commands (names of executables that are existing on the file
        system), and execute them in both the foreground mode (shell waits for
        the execution of the command to complete), and the background mode
        (where shell does not wait for the command to complete). The suffix `&`
        is used to execute a command in the background mode.
    
    3.  Support I/O redirection using `<<<`, `>>>`, and `&>>` operators.
    
    4.  Support command pipelines using `||` (custom) operator.
    
    5.  Control the execution of the commands by interrupting an execution or
        terminating the execution of a command (support `SIGINT`, `SIGSTP`, and
        `SIGCHLD`).
