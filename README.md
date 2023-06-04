# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module

### Step 2: 
Open the file with sys.argv[1]
 
### Step 3: 
Use the for loop to select the content in file

### Step 4:  
Use split function to to separate the file content into words or strings

### Step 5: 
Count the length of the words using len

### Step 6: 
Print the number of words

## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: HARISH RAGAV S
RegisterNumber: 212222110013

import sys
fp=open(sys.argv[1], 'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("No of words in a file",count)
```

### OUTPUT:
![image](https://github.com/harishragav272003/command-line-arguments-to-count-word/assets/119345345/9cd04bab-fc0b-4b7e-b2d9-452bd84c4faa)

![image](https://github.com/harishragav272003/command-line-arguments-to-count-word/assets/119345345/196a044f-db03-4409-a0b0-b7942df57653)

![image](https://github.com/harishragav272003/command-line-arguments-to-count-word/assets/119345345/68920392-530e-452e-b676-a964a52cd3b0)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
