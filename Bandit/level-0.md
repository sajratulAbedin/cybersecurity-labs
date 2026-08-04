# Bandit Leve 0  → Level 

## Goal
The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.
## Command Used

```
 cat readme

```
## password

```
[Hidden for security]

```

## Output

```
<Bandit Level 1 Password>
```

## Explanation

1. `ls` was used to list the files in the current directory.
2. The `readme` file was found in the home directory.
3. `cat readme` displayed the contents of the file.
4. The output was the password for `bandit1`.
5. This password was then used to log in to the next level using SSH.

## What I Learned
- How to connect to Bandit using SSH.
- How to list files using the `ls` command.
- How to read a file using the `cat` command.
- The home directory is the default working directory after login.
- Passwords for the next levels are stored in different files.