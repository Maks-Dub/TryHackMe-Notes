# Linux Fundamentals (NotCompleted)

**Difficulty:** Easy
**Link:** https://tryhackme.com/room/linuxfundamentalspart1
**Date:** October 2026

## Goal

## What I did
- Started a Linux VM to learn some basic Linux commands 

## What I learned

Basic commands:

| Command | What it does | Example |
|---|---|---|
| `whoami` | Shows which user you are on the system | `whoami` |
| `echo` | Outputs the text you give it | `echo "hello"` |
| `pwd` | Print working directory: shows where you are | `pwd` |
| `ls` | Lists what's in the current folder | `ls` |
| `cd` | Change directory: moves you into a folder | `cd Documents` |
| `cat` | Shows the contents of a file | `cat notes.txt` |

## Searching

| Command | What it does | Example |
|---|---|---|
| `find` | Searches for files by name | `find -name passwords.txt` |
| `grep` | Searches inside a file for text | `grep "password123" passwords.txt` |

## Operators

| Operator | What it does |
|---|---|
| `&` | Runs the command in the background, so you can keep using the terminal. Useful for commands that take a while. |
| `&&` | Runs two commands in order, and only runs the second once the first has finished successfully. |
| `>` | Redirects output to a file. **Overwrites** anything already in the file. |
| `>>` | Redirects output to a file, but **appends** to the bottom instead of overwriting. |

## Real-World Link

