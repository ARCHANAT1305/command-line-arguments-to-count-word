# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use the input function to prompt the user to enter the name of the file. Store the input in the variable fname.
### Step 2: 
Set num_words to 0. This variable will be used to store the total number of words in the file. 
### Step 3: 
Use the with open statement to open the file with the name entered by the user in read mode ('r') and use a for loop to iterate over each line in the file.
### Step 4:  
Split each line into words using the split() method.
### Step 5: 
Add the length of the list of words to the num_words variable.
### Step 6: 
After processing all lines in the file, print the total word count.
## PROGRAM:
```Developed By: ARCHANA.T
Register Number:212223240013

fname = input("enter the file name")
num_words=0
with open(fname,'r')as f:
    for line in f:
        words=line.spilt()
        num_words+=len(words)
print('Number of words: ',num_words)        
```
### OUTPUT:
![s2](https://github.com/ARCHANAT1305/command-line-arguments-to-count-word/assets/145975189/d143a23c-d431-4ca1-9efe-94bcd3de5a91)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
