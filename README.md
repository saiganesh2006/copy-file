# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Create a file.
## Step 2:
Write some lines in that file.
## Step 3:
Create a python file.
## Step4:
Write a code to copy the content of the file to a new file.
## Step 5:
Run the program.
## Step 6:
Display the output.

## PROGRAM:
```
Developed By:D.B.V.SAI GANESH
Register No: 212223240025
def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)
```
### OUTPUT:
![image](https://github.com/saiganesh2006/copy-file/assets/145742342/eadec939-5dc5-4eac-a0f7-acd70c675d5d)

# Copied File:
![image](https://github.com/saiganesh2006/copy-file/assets/145742342/271cff83-c219-4a94-88e0-734d39d98fc3)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
