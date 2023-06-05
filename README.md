# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the first file in read mode
### Step 2: 
 Open the second file in append mode
### Step 3: 
Every word in first file is copied to second file using write()
### Step 4:  
close the first file
### Step 5: 
close the second file

## PROGRAM:
```
python program for copying the contents from one file to another file.

Developed by: JEEVITHA S

RegisterNumber: 212222100016

f1=open("sample1.txt","r")
f2=open("sample2.txt","a")
for line in f1:
    f2.write(line)
f1.close()
f2.close()
```
### OUTPUT:
![image](https://github.com/Jeevithha/copy-file/assets/123623197/6bdc7a26-2fc0-4c85-9600-95db9160f094)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
