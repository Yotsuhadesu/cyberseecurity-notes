# Linux Basics

## Commands I've Learned
- Structure: command [flags] file [arguments]
- pwd - show current working location
- ls - show files/folders in the current working directory
- echo - print what you type
- whoami - show the current user's account
- cd - move across directories/folders
- grep - find a specified word
- find - locate a file
- `>` - overwrite a file's content or create one if the file is non-existent
- `>>` - add something to a file
- & - run a command in the background
- && - run two commands; the second command will only run if the first command succeeds
- man - show the manual page of a command
  - man ls

## Flags - modify commands
- ls -l - show files in a long list format
- ls -a / ls --all - show all files, including the hidden ones
- `-r` - operate on a directory and its contents
  - rm -r example_directory
- `--help` - show everything about the command

## Arguments - destination
- `..` - parent directory
  - cd ../.. - move two directories from the current directory
