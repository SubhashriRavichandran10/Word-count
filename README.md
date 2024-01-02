# Word-count
## AIM:
To write a python program for getting the word count from a text.

## EQUIPEMENT'S REQUIRED:
PC Anaconda - Python 3.7

## ALGORITHM:
## Step 1:
Open the file in read mode and handle it in test mood.

## Step 2:
Read the text using read() function.

## Step 3:
Split the text using space separator.We assume that words in a sentance are separted by a space character.

## Step 4:
The length of the split list should equal the numbers of words in the test file.

## Step 5:
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.

## Step 6:
End the program.

## PROGRAM:
```
Developed by : SUBHASHRI R
Registered number: 212223230219

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

## OUTPUT:


![Screenshot 2024-01-02 183809](https://github.com/SubhashriRavichandran10/Word-count/assets/145743413/46bf980a-31d4-43fa-a8f5-886e2ad36519)

![Screenshot 2024-01-02 183833](https://github.com/SubhashriRavichandran10/Word-count/assets/145743413/917932f6-0510-4ffb-89fe-19bfa7f54db7)

![Screenshot 2024-01-02 183847](https://github.com/SubhashriRavichandran10/Word-count/assets/145743413/b7e0ba18-9cb5-4d50-9d8e-482467216a3e)


## RESULT:
Thus the program is written to find the word count from a text.
