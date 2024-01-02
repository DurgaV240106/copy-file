# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required the from which we need to copy the text.
### Step 2: 
Using keyword "with" to open the required file. 
### Step 3: 
Again using the with keyword to open the empty file.
### Step 4:  
The empty file is open by using 'W' which is used to write only.
### Step 5: 
The for function is used to take each line from the main file.
### Step 6: 
Write() is used to write the lines of main file to the empty file or to the directed file.
## PROGRAM:
```
def copy(fname,newfile):
    with open(fname,'r')as fp:
        with open(newfile,'w')as fp1:
            data1=fp.read()
            fp1.write(data1)
fname=input("Enter an existing file: ")
newfile=input("Enter a name for new file: ")
copy(fname,newfile)
```

### OUTPUT:
<img width="605" alt="Screenshot 2024-01-03 012409" src="https://github.com/DurgaV240106/copy-file/assets/144870878/1ba1ab3e-5fdf-4fd8-85cb-65131ee90b57">
<img width="586" alt="Screenshot 2024-01-03 012427" src="https://github.com/DurgaV240106/copy-file/assets/144870878/ddd29a40-f1f5-4783-9e4a-1c1cd34858cd">
<img width="685" alt="Screenshot 2024-01-03 012713" src="https://github.com/DurgaV240106/copy-file/assets/144870878/2054256c-81b2-4274-ac6a-8d61ae9764e9">



## RESULT:
Thus the program is written to copy the contents from one file to another file.
