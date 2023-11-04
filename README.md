# Copy-file

## AIM:
To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1: 

Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2: 

Read the file and store in a variable.
 
### Step 3: 

Now create a new file in which we want to paste the content using write access mode.

### Step 4:  

Use write function to copy the read file that has been stored in the variable.

### Step 5: 

The content in the original file will be copied in the new file.

### Step 6: 

End the program.

## PROGRAM:

Developed by : SUBALAKSHMI.S

Register Number : 212222100051

```py
with open('file1.txt','r') as firstfile:
    with open('file2.txt','a') as secondfile:
        for line in firstfile:
            secondfile.write(line)
```

## OUTPUT:

![image](https://github.com/Subalakshmisuresh/copy-file/assets/121957896/1c78d5da-0276-4158-9f6b-22324712f947)

![image](https://github.com/Subalakshmisuresh/copy-file/assets/121957896/6071d8bb-ec68-4e98-a9dc-2d2175d6e48c)




## RESULT:
Thus the program is written to copy the contents from one file to another file.


