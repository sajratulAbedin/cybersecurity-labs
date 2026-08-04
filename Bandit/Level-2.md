# Bandit Level 2  → Level 3 

## Goal
The password for the next level is stored in a file called --spaces in this filename-- located in the home directory
## Command Used

```"
cat "./--spaces in this filename--"

```

## Output

```
<password for level 3>
```

## Explanation

1. Used `ls` to list the files in the current directory.
2. Found a file named `--spaces in this filename--`.
3. A filename of `--spaces in this filename--` is treated specially by many Linux commands, so `cat -` would not read the file.
4. Used `cat "./--spaces in this filename--"` to specify that `--spaces in this filename--` is a filename in the current directory.
5. The file's contents were displayed, revealing the password for the next level.

## What I Learned
- A filename can be a special character like `--spaces in this filename--`.
- `cat --spaces in this filename--` does **not** read a file named `--spaces in this filename--`; it reads from standard input (stdin).
- Prefixing the filename with `"./"` tells Linux to treat it as a file in the current directory.
- `ls` helps identify files before accessing them.
- Understanding special filenames is important when working with Linux.