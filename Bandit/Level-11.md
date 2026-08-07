# Bandit Level 11 → Level 12

## Goal
The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions

## Command Used

```
 
  cat data.txt | tr "A-Za-z" "N-ZA-Mn-za-m"


```

## Output

```
<password for level 12>
```

## Explanation

1. Used ` cat data.txt | tr "A-Za-z" "N-ZA-Mn-za-m" ` that command to is used to translet alphabet rotated by 13 possitions .
 
 

## What I Learned

- cat
- ROT13 Mean=tr "A-Za-z" "N-ZA-Mn-za-m"

   






