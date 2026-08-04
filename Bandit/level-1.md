# Bandit Level 1  → Level 2 

## Goal
find password from   a file called - located in the home directory
## Command Used

```
ls
cat ./-
```

## Output

```
<level 2 password>
```

## Explanation

1. Used `ls` to list the files in the current directory.
2. Found a file named `-`.
3. A filename of `-` is treated specially by many Linux commands, so `cat -` would not read the file.
4. Used `cat ./-` to specify that `-` is a filename in the current directory.
5. The file's contents were displayed, revealing the password for the next level.

## What I Learned
- A filename can be a special character like `-`.
- `cat -` does **not** read a file named `-`; it reads from standard input (stdin).
- Prefixing the filename with `./` tells Linux to treat it as a file in the current directory.
- `ls` helps identify files before accessing them.
- Understanding special filenames is important when working with Linux.