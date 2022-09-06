# Bash Practice

## The Command Line

- What is it?

A command line, or terminal, is a text based interface to the system.

- How does it work and how do I get to one?

You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

---

## Basic Navigation

An introduction to the Linux directory system and how to get around it:

```
pwd
```

which stands for Print Working Directory.

Its mean what your current or present working directory is.

```
ls
```

It's short for list.

```
-l
```

Its tells the command to use a long list format. It gives back several columns wich correspond to:

- Permissions
- Number of hardlinks
- File owner
- File group
- File size
- Modification time
- Filename

---

## More About Files

Find out some interesting characteristics of files and directories in a Linux environment.

-Everything is a file under Linux
Even directories.

-Linux is Case Sensitive.

-When I have spaces in names, I should write it with

**Quotes**
```
'Holiday Photos'
```

 or **Escape Characters**
 ```
Holiday\ Photos
```
-To show the Hidden Files and Directories
```
ls -a
```

---

## Manual Pages




| command | Description |
| ----------- | ----------- |
| `man <command>` | Look up the manual page for a particular command |
| `man -k <search term>` | Do a keyword search for all manual pages containing the given search term |
| `/<term>` | Within a manual page, perform a search for 'term' |
| `n` | After performing a search within a manual page, select the next found item |


---

## File Manipulation

- How to make, remove, rename, copy and move files and directories.

| command | Description |
| ----------- | ----------- |
| `mkdir` | Make Directory - ie. Create a directory |
| `rmdir` | Remove Directory - ie. Delete a directory|
| `touch` | Create a blank file |
| `cp` | Copy - ie. Copy a file or directory |
| `mv` | Move - ie. Move a file or directory (can also be used to rename) |
| `cp` | Remove - ie. Delete a file |

