# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Give the values from the user
### Step 2:
Assign the value of second variable to a temporary variable
### Step 3: 
Assign the value of the first variable to the second variable
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
print the both value it would be interchanged
### Step 6:
End the program 
## Program:
~~~
#Program to circulate N values.
#Developed by:Meiyarasi.V
#RegisterNumber:21005984
def circulate():
    X = [10,20,30,40,50,60]
    n = int(input())
    X = X[n:]+X[:n]
    print("After circulating the values are:",X)
~~~
## Output:
![output](.//CN.png)

## Result:
thus the circulate the valus of n variables is executed
