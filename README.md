# OVERTHEWIRE (BANDIT)

## LEVEL 0->1
### Solucion 
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```
```bash
ls
```
```bash
cat readme
```
 ### Password
```bash
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```

## LEVEL 1->2
### Solucion 
```bash
ssh bandit1@bandit.labs.overthewire.org -p 2220
```
```bash
ls
```
```bash
cat ./-
```
 ### Password
```bash
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```

## LEVEL 2->3
### Solucion 
```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220
```
```bash
ls
```
```bash
cat "spaces in this filename"
```
 ### Password
```bash
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
```

## LEVEL 3->4
### Solucion 
```bash
ssh bandit3@bandit.labs.overthewire.org -p 2220
```
```bash
ls
```
```bash
cd inhere
```
```bash
ll
```
```bash
cat ...Hiding-From-You
```
 ### Password
```bash
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
```

## LEVEL 4->5
### Solucion 
```bash
ssh bandit4@bandit.labs.overthewire.org -p 2220
```
```bash
ls
```
```bash
cd inhere
```
```bash
ls
```
```bash
find . | xargs file
```
```bash
cat ./-file07
```
 ### Password
```bash
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
```

## LEVEL 5->6
### Solucion 
```bash
ssh bandit5@bandit.labs.overthewire.org -p 2220
```
```bash
ls
```
```bash
cd inhere/
```
```bash
ls
```
```bash
find . -type f -readable -size 1033c ! -executable
```
```bash
cat ./maybehere07/.file2
```
 ### Password
```bash
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
```

## LEVEL 6->7
### Solucion 
```bash
ssh bandit6@bandit.labs.overthewire.org -p 2220
```
```bash
find / -user bandit7 -group bandit6 -size 33c | xargs cat
```
```bash
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null | xargs cat
```
 ### Password
```bash
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
```

## LEVEL 7->8
### Solucion 
```bash
ssh bandit7@bandit.labs.overthewire.org -p 2220
```
```bash
ls
```
```bash
cat data.txt | grep millionth
```
 ### Password
```bash
dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
```

## LEVEL 8->9
### Solucion 
```bash
ssh bandit8@bandit.labs.overthewire.org -p 2220
```
```bash
ls
```
```bash
sort data.txt | uniq -u
```
 ### Password
```bash
4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
```

## LEVEL 9->10
### Solucion 
```bash
ssh bandit9@bandit.labs.overthewire.org -p 2220
```
```bash
ls
```
```bash
strings data.txt
```
```bash
strings data.txt | grep ==
```
 ### Password
```bash
FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
```

## LEVEL 10->11
### Solucion 
```bash
ssh bandit10@bandit.labs.overthewire.org -p 2220
```
```bash
ls
```
```bash
cat data.txt | base64 -d
```
 ### Password
```bash
dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
```

## LEVEL 11->12
### Solucion 
```bash
ssh bandit11@bandit.labs.overthewire.org -p 2220
```
```bash
ls
```
```bash
cat data.txt
```
```bash
cat data.txt | tr '[A-Za-z]' '[N-ZA-Mn-za-m]'
```
 ### Password
```bash
7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
```

## LEVEL 12->13
### Solucion 
```bash
ssh bandit12@bandit.labs.overthewire.org -p 2220
```
```bash
ls
```
```bash
cat data.txt
```
```bash
man xxd
```
```bash
mkdir /tmp/eddy
```
```bash
cp data.txt /tmp/eddy
```
```bash
cd /tmp/eddy
```
```bash
man xxd
```
```bash
xxd -r data.txt > info
```
```bash
mv info info.gz
```
```bash
gzip -d info.gz
```
```bash
mv info info.bz2
```
```bash
bzip2 -d info.bz2
```
```bash
mv info info.gz
```
```bash
gzip -d info.gz
```
```bash
man tar
```
```bash
mv info info.tar
```
```bash
tar -xf info.tar
```
```bash
mv data5.bin data5.bin.tar
```
```bash
tar -xf data5.bin.tar
```
```bash
rm info.tar data5.bin.tar data.txt
```
```bash
mv data6.bin data6.bin.bz2
```
```bash
mv data6.bin data6.bin.bz2
```
```bash
mv data6.bin data6.bin.tar
```
```bash
tar -xf data6.bin.tar 
```
```bash
mv data8.bin data8.bin.gz
```
```bash
gzip -d data8.bin.gz
```
```bash
cat data8.bin
```
 ### Password
```bash
FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
```

## LEVEL 13->14
### Solucion 
```bash
ssh bandit13@bandit.labs.overthewire.org -p 2220
```
```bash
ssh -i sshkey.private bandit14@localhost -p 2220
```
```bash
cat /etc/bandit_pass/bandit14
```
 ### Password
```bash
MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
```

## LEVEL 14->15
### Solucion 
```bash
ssh bandit14@bandit.labs.overthewire.org -p 2220
```
```bash
nc localhost 30000
```
```bash
MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
```
 ### Password
```bash
8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
```

## LEVEL 15->16
### Solucion 
```bash
ssh bandit15@bandit.labs.overthewire.org -p 2220
```
```bash
ncat --ssl localhost 30001
```
```bash
8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
```
 ### Password
```bash
kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx
```
