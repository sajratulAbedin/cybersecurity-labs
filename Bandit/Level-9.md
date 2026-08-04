# Bandit Level 9 → Level 10

## Goal
The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.

## Command Used

```
 
 strings data.txt | grep "="
```

## Output

```
<password for level 10>
```

## Explanation

1. Used ` strings data.txt | grep "="` that command to is used to extract and display human-readable (printable) text strings from binary or non-text files .
 
2.  here we piping using grep command.grep command search a specific word from a text file

## What I Learned

- strings
- grep
   






