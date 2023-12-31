# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.
### Step 2: 
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1] 
### Step 3: 
Read the file using read() method.
### Step 4:  
Use split() method to split the file content into words.
### Step 5: 
Use len() to find the total words.
### Step 6: 
Run the program to determine the number of words in the file created.
## PROGRAM:
```
# Python program for getting the word count from the contents of a file using command line arguments.
# Developed by: jagadeesh p
# Register number: 23013534
import sys
fp= open(sys.argv[0])
data=fp.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:
![Screenshot 2023-12-31 204446](https://github.com/jagadeesh9500/command-line-arguments-to-count-word/assets/149087921/dc98d5cc-0824-4813-9d2a-454a5242fcc4)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
