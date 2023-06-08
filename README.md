# Word Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
- PC , Anaconda - Python 3.7
## ALGORITHM: 
- Step 1: Open then required file by using the function"with"
- Step 2: Using split function to split the words. 
- Step 3: Finding the length of the words by using len() function.
- Step 4: Calling the function and printing the number of words.
## PROGRAM:
```Python
#Developed By: ROHIT JAIN D
#Register No: 212222230120
n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
    for line in f:
        words=line.split()
        wordslen+=len(words)
print("Number of wordds:",wordslen)
```
#### File content:
<img height=10% src="https://github.com/ROHITJAIND/Word-count/assets/118707073/a63e12c2-759c-4594-ab7d-a9ec99a064e3">

### OUTPUT:
![Screenshot 2023-06-08 111530](https://github.com/ROHITJAIND/Word-count/assets/118707073/02b95ca4-0cf7-4b16-b681-fb0cd1aeaba3)

## RESULT:
Thus the program is written to find the word count from a text.
