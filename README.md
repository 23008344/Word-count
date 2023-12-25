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

![image](https://github.com/23008344/Word-count/assets/145742655/bbc3b53b-5a3d-4dfc-9a61-c2bdace13f84)

![image](https://github.com/23008344/Word-count/assets/145742655/263917c0-4566-4c32-b4b7-a1280febd04b)

![image](https://github.com/23008344/Word-count/assets/145742655/b01526fd-0a00-484f-92c2-c84d18d83102)


## RESULT:
Thus the program is written to find the word count from a text.
