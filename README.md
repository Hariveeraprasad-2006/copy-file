# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First create a two files. one for input file and one for output file
### Step 2: 
After that write a sentence in input file
### Step 3: 
Then open the input file and read it
### Step 4:  
After that open the second file and use append mode to it. 
### Step 5: 
Then use for loop to the copy the sentence in f1 to f2
### Step 6: 
Then run the programme 
## PROGRAM:
```
#Developed By: Arikatla Hari Veera Prasad
#Register Number:212223240014
with open('PYTHON.txt','r') as f1:
    with open ('PYTHON2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
![image](https://github.com/Hariveeraprasad-2006/copy-file/assets/145049988/4b635fdd-7b90-4581-9d96-dde34329b491)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
