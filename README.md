# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
## Step 1:

create a function with keyword and name
## Step 2:

get input for the variable list and range
## Step 3:

Get the value from the user for the number of rotation
## Step 4:

Using the slicing concept rotate the list
## Step5:

the circulated number will be recieved
## Step 6:

End the program
## Program:
```python
#Program to circulate N values.
#Developed by:Jivan Karthec.B.S 
#RegisterNumber:22004763
def circulate():
    a=eval(input())
    b=int(input())
    a=a[b:]+a[:b]
    print("After circulating the values are:",a)

## Output:

## Result:
