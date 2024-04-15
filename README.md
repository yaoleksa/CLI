# Project quick manual
`initp` is a handy CLI (command line interface) designed for a quick Python project initialization.
The most convenient and fastest way to get list of existing options is to install program on macine, and after that open terminal and type `initp -h` or `initp --help`, but just in case I duplicate the list of commands here.
```
usage: initp [-h] [-f FILENAME] [-r REQUIREMENTS [REQUIREMENTS ...]] [-v] [-d]
             [name ...]

positional arguments:
  name                  Specifies the name of the Python project which will be
                        created

options:
  -h, --help            show this help message and exit
  -f FILENAME, --filename FILENAME
                        Specifies the file name of your program. If this
                        option is skipped "main.py" will be used as the
                        default filename
  -r REQUIREMENTS [REQUIREMENTS ...], --requirements REQUIREMENTS [REQUIREMENTS ...]
                        Defines which non-built-in libraries are mandatory for
                        your program. If this option is skipped it treats like
                        your program does not need any non-built-in libraries
  -v, --version         Shows the current version of this program
  -d, --readme          If this option is passed it creates a readme file
  ```
  > [!IMPORTANT]
  > First of all, you have to download this repository locally on the machine to execute the following actions. You can achieve this goal in two ways: by running `git clone REPOSITORY-URL` into the terminal or manually downloading the .zip archive and unzipping it where you want

  > [!TIP]
  > I deeply recommend using the approach with CLI git cause it is more professional, but it is up to you which approach to use.
  
  After you download the repository locally, to install the program just run Install file. Run this file you can with two approaches:
  - Click on the file with the right-hand button mouse then click `Run as program` on the drop-down list of options
  - Open the terminal and type `sudo ./Install`
  > [!TIP]
  > As with the previous case, I recommend using the approach with a terminal