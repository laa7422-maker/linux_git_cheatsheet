# Linux & Git Command Cheat Sheet

A quick-reference guide to essential Linux and Git commands.

---

## Table of Contents
- Linux Commands
- Git Commands

---

### `cd` — Change Directory
```bash
cd /home/user    # go to absolute path
cd ..            # go up one level
cd ~             # go to home directory

### `pwd` — Print Working Directory
```bash
pwd    # outputs current path, e.g. /home/user/projects

### `mkdir` — Make Directory
```bash
mkdir myfolder        # create a single folder
mkdir -p a/b/c        # create nested directories

### `rm` — Remove Files or Directories
```bash
rm file.txt           # delete a file
rm -rf myfolder/      # force-delete a directory recursively

### `cp` — Copy Files or Directories
```bash
cp file.txt backup.txt        # copy a file
cp -r folder/ newfolder/      # copy a directory recursively

### `mv` — Move or Rename Files
```bash
mv old.txt new.txt       # rename a file
mv file.txt /tmp/        # move file to another directory

### `chmod` — Change File Permissions
```bash
chmod 755 script.sh     # rwx for owner, rx for group and others
chmod +x script.sh      # add execute permission for everyone

### `git init` — Initialize a Repository
```bash
git init    # creates a .git folder in the current directory

