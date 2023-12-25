# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
start the program
### Step 2: 
open the file in read mode
### Step 3: 
find the no of words in a file
### Step 4:  
end the program


## PROGRAM:
```
'''
Developed by: VARNIKA.P
Registered number: 23008344
'''
num_words=0
with open('5a.txt','r') as f1:
    for i in f1:
        word=i.split()
        num_words += len(word)
print("Number of words in the file = {}".format(num_words))



```
### OUTPUT:

![Alt text](<Screenshot 2023-12-25 180904.png>)
![Alt text](<Screenshot 2023-12-25 180925.png>)
![Alt text](<Screenshot 2023-12-25 180944.png>)

## RESULT:
Thus the program is written to find the word count from a text.
