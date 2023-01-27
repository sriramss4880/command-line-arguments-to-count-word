# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Import the sys module.

Step 2:
Pass the filename as the first argument after the name of script.Open the file as sys.argv[1]

Step 3:
Read the file using read() method.

Step 4:
Use split() method to split the file content into words.

Step 5:
Use len() to find the total words.

Step 6:
Run the program to determine the number of words in the file created

## PROGRAM:
```python
Program to sort the elements in the list using the Selection Sort algorithm.
Developed by: S.S.Sriram
RegisterNumber: 22004880
import sys
count = 0
with open(sys.argv[1],'r')as f1:
    for line in f1:
        word = line.split()
        count += len(word)
print("word count in file = ",count)
```
### OUTPUT:
![image](https://user-images.githubusercontent.com/120554177/215004064-39f808a5-9745-4f9b-98fd-fe89351e7859.png)
![image](https://user-images.githubusercontent.com/120554177/215004081-4fc79dd2-9059-4cd3-907b-89ebe89a0d72.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
