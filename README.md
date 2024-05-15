# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

## Step 1:
Create a text file with some content in it.

## Step 2:
Open the created text file.

## Step 3:
Create another empty text file.

## Step 4:
Copy the content of text file to empty file using write function.

## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by: RAHINI.A
#Register Number: 212223230165

with open("text1.txt","r") as fp:
msg1=fp.read()
with open("copytext.txt","w") as fp1:
fp1.write(msg1)
```
### OUTPUT:
![WhatsApp Image 2024-05-15 at 22 36 44_4123a677](https://github.com/RahiniAchudhan/Copy-File/assets/145742838/97129bd4-f110-49c3-828a-bb084331d729)
![WhatsApp Image 2024-05-15 at 22 36 40_83a4fbf0](https://github.com/RahiniAchudhan/Copy-File/assets/145742838/6e367d6e-d185-4aec-a082-5726e1c9570b)

![WhatsApp Image 2024-05-15 at 22 36 36_f29055b8](https://github.com/RahiniAchudhan/Copy-File/assets/145742838/7db25e57-c12a-49ac-b1b4-4c96f4463530)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
