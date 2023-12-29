# Copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
Write some lines in that file
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
```
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
![ex5csample](https://github.com/GnanendranN/copy-file/assets/138955207/9cc44af7-feba-43de-b202-d235f55102b3)

![ex5ccopy](https://github.com/GnanendranN/copy-file/assets/138955207/0320932a-e38b-4120-88c0-8ab2751a0a59)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
