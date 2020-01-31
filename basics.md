# Basics
Shell is a part of the operating system how the terminal will behave. Bash is kind of shell. Commands are case-sensitve and space used as a default separator.

### Structure of a command
`ls -l /home/robert` where:
- ls is the command
- -l /home/robert is arguments
  - -l called an option

### Paths
Every path which begins with **/** is an absolute path. **/** means the root directory. Anything else is called relative path.
- **~**: stands for your home directory
- **.**: current directory

### Important directories
- `/etc:`config files for system
- `/var/log:`   log files
- `/bin`: commonly used programs
- `/usr/bin:` another location for programs



#### Commands
Command options have a short version, and long version. Short begins with -, long version with --. Short options can be appended after eachother.
- `pwd:` where I am
- `ls: ` lists contents of a directory (except hidden files, these begins with **.**)
    - `ls -l:` long listing: `drwxr-xr-x  2 ryan users 4096 Mar 23 13:34 bin`
      - first character: **-** for normal file, **d** for directory
      - next 9 characters are permissions
      - **ryan** is the the file or directory owner
      - **users** the group the file/directory belongs to
      - **4096** is the size
    - `ls -a`: lists hidden files also
- `cd`: change directory
  - if name contains *space* in it, put path in '`path`'
- `file:` gives information about file type
- `man`: manual page of a given command
  - pressing q to exit from manual page
