# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define a function called circulate to cirulate the n variables.
### Step 2: 
The function will circulate the n variables as per the input given.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print the circulated output as per the input given.
### Step 6: 
End the program.
## Program:
~~~
#Program to circulate N values.
#Developed by: 
#RegisterNumber:
def circulate():
    l=[10,20,30,40,50,60]
    n=int(input())
    r=l[n:]+l[:n]
    print("After circulating the values are:",r)
~~~
## Output:
![github logo](circulate.png)
## Result:
Thus, a python program to circulate the n variables using function concept is executed successfully.