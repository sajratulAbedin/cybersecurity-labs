# Bandit Level 6 → Level 7

## Goal
The password for the next level is stored somewhere on the server and has all of the following properties:

owned by user bandit7
owned by group bandit6
33 bytes in size

## Command Used

```
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
```

## Output

```
<password for level 7>
```

## Explanation

1. Used `find / -user bandit7 -group bandit6 -size 33c 2>/dev/null` command to find the file path.
2. cat cat /var/lib/dpkg/info/bandit7.password used to display file password
 


## What I Learned

- find  
- user
- group 
- size  






