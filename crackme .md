The challenge  gave us unlock pdf file  and asked me to crack this file
![shpass2](https://github.com/MohmmadOd/BAUctf/assets/170467994/9a23ea11-65e6-4d2c-b39f-0c924d7dba47)

This was easy and straight forward challenge , so first thing I made sure this file is pdf file by file command , now I wanna crack the file so I used pdf2john command and put it in file name hash.txt .then, I used john --wordlist=/usr/share/wordlists/rockyou.txt  hash.txt 
 command john: This is the main command to run John the Ripper ,
john --wordlist=/usr/share/wordlists/rockyou.txt : This specifies the wordlist to be used for the password cracking attempt. The RockYou wordlist is a common list of passwords that were leaked from the RockYou.com website and is often used in password cracking due to its extensive collection of real-world passwords, 
hash.txt : file name 
when run it I got the password the put it 


