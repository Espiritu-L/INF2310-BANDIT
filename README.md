# OVERTHEWIRE (BANDIT)

## LEVEL 0
The goal of this level is for you to log into the game using SSH.  
The host to which you need to connect is `bandit.labs.overthewire.org`, on port `2220`.  
The username is `bandit0` and the password is `bandit0`.  
Once logged in, go to the Level 1 page to find out how to beat Level 1.
### Solucion 
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```
 ### Pasword
```bash
bandit0
```

## LEVEL 1
The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.
### Solucion 
```bash
ssh bandit1@bandit.labs.overthewire.org -p 2220
```
 ### Pasword
```bash
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```
