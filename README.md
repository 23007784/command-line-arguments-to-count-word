# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import the sys.
### Step 2: 
 Open the file and assign it to f1.
### Step 3: 
Read the file and assign it to data.
### Step 4:  
split the data(data.split()).
### Step 5: 
print the word count by len(word).
### Step 6: 
colse the file f1.
## PROGRAM:
```PYTHON
#python program for word count
#developed by : NIKSHITHA G
#reference number: 23007784
import sys
f1=open(sys.argv[0])
data=f1.read()
word=data.split()
print("The word count is",len(word))
f1.close()
```
### OUTPUT:
![Alt text](<command line.png>)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
