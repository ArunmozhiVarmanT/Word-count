# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
```
\*
#Program to find the Word Count
#Developed by: ARUNMOZHI VARMAN T
#Register number: 23002304
\*
num=0
with open("/content/story.txt","r") as f1:
  for i in f1:
    word=i.split()
    num+=len(word)
print("The number of words in the file is ",num)
```
### OUTPUT:
![Screenshot 2024-01-03 115246](https://github.com/ArunmozhiVarmanT/Word-count/assets/144870523/0b9ba766-eb45-4606-9995-b58d283a8940)

## RESULT:
Thus the program is written to find the word count from a text.
