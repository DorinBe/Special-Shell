# Implementation Of Shell
Second year C project. Project demands are to write some functions in C language which run under UNIX(centos 7).  
The shell will support all the ordinary commands (such ls -l, mkdir...), and also couple of other functions (listed below).  

int encryptFile(char* from, int code, char* to)  
*Function encrypts the file "from" by adding "code" to the ascii value of the characters in the file.*  

int decryptFile(char* from, int code, char* to)  
Function decrypts the file "from" by decreasing "code" from the ascii value of the characters in the file.  

int letterFreq(char* from)  
Function scans the file 'from' and finds three ABC letters that occur most of the time.  
Than, prints their frequency, and if the order of those three letters is a-e-o  
than it prints "Good Letter Frequency".  

int uppercaseByIndex(char* from, char* to, int index)  
Function scans each word in file 'from' and transforms word[index] to uppercase.  

int lowercaseByIndex(char* rFile, char* wFile, int index)  
Function scans each word in file from and transforms word[index] to lowercase.  

int randomFile(int num, char* wFile)  
Function writes "num" random ABC letters to 'wFile'  

int compressFile(char* pathOpen, char* pathSave)  
Function receives two paths, it scans the file of 'pathOpen',  
and compresses the words which occur more than 4 times in a row.  

int lockCmdForTime(char* cmdToLock, int lockDuration, Node** listLockedCmds)  
Functions prevents the use of a given command by using linked list of locked commands.

![alt text](https://user-images.githubusercontent.com/90141260/133922724-5a298a1e-749d-4842-827b-0b11f18c5add.png)
![alt text](https://user-images.githubusercontent.com/90141260/133922725-75cdb4c0-345b-4a56-a10f-be134e64b927.png)
