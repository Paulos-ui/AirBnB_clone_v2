# HBNB- The console
Welcome to my readme file
This repository contains the initial stage of a group airBnB project to build a clone of the AirBnB website. This stage implements a backend interface, or console, to manage program data. Console commands allow the user to create, update, and destroy objects, as well as manage file storage. Using a system of JSON serialization/deserialization, storage is persistent between sessions.

## Resipository content by the project task given :
\
change to the *AirBnb* directory and run the command:
` ./console.py `

### Execution

In interactive mode:
```
$ ./console.py
(hbnb) help
EOF  help  quit
(hbnb)
(hbnb)
(hbnb) quit
$
```

In non interactive mode:

```
$ echo "help" | ./console.py
(hbnb)
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)
EOF  help  quit
(hbnb) 
$
```
### 0x04 Testing

All the test will be on the *test* folder

### 0x05 Usage

+ Start the console in interactive mode:

`$ ./console.py
(hbnb)`

# Authors:
* Khaoula Ouardi
* Jayeoba Tunmise
