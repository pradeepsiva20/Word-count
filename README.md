# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open terminal and activate conda, then open jupyter notebook.
### Step 2: 
Create a text file in jupyter notebook or upload a text file in the jupyter notebook. 
### Step 3: 
Open a new cell in jupyter notebook.
### Step 4:  
Type the program in the cell.
### Step 5: 
Now in the output box,type the file name.
### Step 6: 
End the program.
## PROGRAM:
#Developed by: PRADEEP.S
#Reference No: 22009034

fname=input("Enter file name: ")
num_words=0
with open(fname,'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print("Number of words: ",num_words)

 OUTPUT:
![Screenshot from 2023-01-26 16-16-09](https://user-images.githubusercontent.com/120539823/214819853-333ae823-c143-4321-b43d-c3dab95ea63e.png)
![Screenshot from 2023-01-26 16-15-23](https://user-images.githubusercontent.com/120539823/214819889-bcf58edd-2119-4633-948f-a349b82a7c15.png)

## RESULT:
Thus the program is written to find the word count from a text.
