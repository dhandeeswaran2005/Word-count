# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.
### Step 2: 
 Read the text using read() function.
### Step 3: 
Split the text using space separator.We assume that words in a sentance are separted by a space character.
### Step 4:  
The length of the split list should equal the numbers of words in the test file.
### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
End the program.
## PROGRAM:
```
'''
developed by:MOHAMED FAROOK 
REGISTER NUMBER: 23014058

'''
num_words=0
with open('5a.txt','r') as f1:
    for i in f1:
        word=i.split()
        num_words += len(word)
print("number of qords in the file = {}".format(num_words))
```
### OUTPUT:
![image](https://github.com/MOHAMEDFAROOK2005/Word-count/assets/150319482/020f6d06-7908-4e1f-8dac-a7722e40ff63)



## RESULT:
Thus the program is written to find the word count from a text.
