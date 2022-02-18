# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
create a list to rotate a list of elements.
### Step 2: 
define a list of elements.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### step 5:
Print the result list the values would be circulated according to the number of rotation value given by the user
### step 6:
End the program
## Program:
~~~
def circulate():
    n=int(input())
    l=[10,20,30,40,50,60]
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
~~~

## Output:
![GitHub Logo](CIRCULATE.jpeg)

## Result:
PROGRAM FINISHED SUCCESSFULLY.
