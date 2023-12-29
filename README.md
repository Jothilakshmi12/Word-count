# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in text mode.
### Step 2: 
 Read the text using read() function.
### Step 3: 
Split the text using space separator.We assume that words in a sentence are separated by space character.
### Step 4:  
The length the split list should equal the numbers of the word in text file.
### Step 5: 
You can trefine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
End the program.
## PROGRAM:
```
Developed By: Jothilakshmi
Register Number: 212223110017
'''
def wordcount(filename):
    count=0
    with open(filename,"r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1 
    print("Total number of words:",count)
filename=input("Enter Filename:")
wordcount(filename)
```

### OUTPUT:
![wordcountoutput1](https://github.com/Jothilakshmi12/Word-count/assets/138849182/338e158e-44ae-407c-b039-54b13f164c11)
![worldcountoutput2](https://github.com/Jothilakshmi12/Word-count/assets/138849182/b0319d13-7b34-4408-8433-5a1629bb1728)


## RESULT:
Thus the program is written to find the word count from a text.
