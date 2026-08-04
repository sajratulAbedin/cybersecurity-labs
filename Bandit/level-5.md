# Bandit Level 5 → Level 6

## Goal
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

human-readable
1033 bytes in size
not executable

## Command Used

```
- find the path

find . -type f -size 1033c ! -executable  

- read the file 

cat ./maybehere07/.file2
```

## password

```

```

## Explanation



## What I Learned

- find  
- type  
- size  
- c = bytes  
- ! = NOT  
- executable



