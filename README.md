# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file.

### Step 2:
Open the required file by using the function "with".

### Step 3: 
Then use the laptop to assign the i value in the file.

### Step 4:
Using split function to spilt the words.

### Step 5:
Finding the given length of the words by using len() fuction.

### Step 6:
Calling the function and Printing the number of words.

## PROGRAM:
```
'''
#Program to count number of words in the text file
#Developed by:V.S.JANANI
#Register no:22003192
'''

num_word=0
with open('nachi.txt') as f6:
    for i in f6:
        word=i.split()
        num_word+=len(word)
print("Number of words:{}".format(num_word))
```

### OUTPUT:
![Screenshot from 2022-09-26 14-12-46](https://user-images.githubusercontent.com/113497333/192232743-0a972777-836f-4f53-a41c-edc25760d196.png)

![Screenshot from 2022-09-26 14-13-51](https://user-images.githubusercontent.com/113497333/192233047-1669b17a-fcc7-4e95-8268-5e5da9043849.png)






## RESULT:
Thus the program is written to find the word count from a text.
