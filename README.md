# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name.
### Step 2: 
Now create a new file to copy the text.
### Step 3: 
Read the file and close it.
### Step 4:  
Now the conten is copied to new file using write function.
### Step 5: 
The print file copied.

## PROGRAM:
```
#Program to copy the file.
#Developed by: Sanjay Balaji
#RegisterNumber: 23005804
print("Enter the name of source file: ")
sFile=input()
print("Enter the name of target file: ")
tFile=input()
fileHandle=open(sFile,"r")
texts=fileHandle.readlines()
fileHandle.close()
fileHandle=open(tFile, "w")
for s in texts:
   fileHandle.write(s)
fileHandle.close()
print("\nFile Copied Successfully!")
```
### OUTPUT:
![image](https://github.com/SanjayBalaji0/copy-file/assets/145533553/309a9b4a-9966-4288-992b-c852224c7bcb)

![image](https://github.com/SanjayBalaji0/copy-file/assets/145533553/785de2f3-41bd-4685-95ea-a9933cff1aa5)

![image](https://github.com/SanjayBalaji0/copy-file/assets/145533553/2c1019de-c91c-4b0d-8cb0-068659714eb9)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
