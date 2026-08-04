# Bandit Level 8 → Level 9

## Goal
The password for the next level is stored in the file data.txt and is the only line of text that occurs only once

 

## Command Used

```
 sort data.txt | uniq -u

```

## Output

```
<password for level 9>
```

## Explanation

1. Used `sort data.txt | uniq -u ` that command to sort the text file and search a unique .
 2. here we piping using uniq -u command.uniq -u command  used to identify unique word from text file


## What I Learned

- sort
- uniq -u
   






