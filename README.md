# Description

HolbertonBnB is a complete web application, integrating database storage, a back-end API, and front-end interfacing in a clone of AirBnB.
The project currently only implements the back-end console.

# Console

The console is a command line interpreter that permits management of the backend of HolbertonBnB. It can be used to handle and manipulate all classes utilized by the application.

# Using the Console

The HolbertonBnB console can be run both interactively and non-interactively. To run the console in non-interactive mode, pipe any command(s) into an execution of the file console.py at the command line.

``` bash 
    $ echo "help" | ./console.py
    (hbnb) 
    Documented commands (type help <topic>):
    ========================================
    EOF  all  count  create  destroy  help  quit  show  update

    (hbnb) 
    $ 
```

Alternatively, to use the HolbertonBnB console in interactive mode, run the file console.py by itself:

``` bash
    $ ./console.py
``` 

While running in interactive mode, the console displays a prompt for input:

``` bash
    $ ./console.py
    (hbnb) 
```

To quit the console, enter the command quit, or input an EOF signal (ctrl-D).

``` bash
    $ ./console.py
    (hbnb) quit
    $
```

``` bash
    $ ./console.py
    (hbnb) EOF
    $
```