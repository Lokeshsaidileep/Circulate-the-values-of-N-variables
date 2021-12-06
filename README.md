# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Get the values from the user
### Step 2: 
Assign the values of the second variable to the temporary variable
### Step 3: 
Assign the value of the first variable to the second variable.
### Step 4: 
Get the value from the user for the number of rotation
### Step 5: 
Using the slicing concept rotate the list
### Step 6: 
End the program
## Program:
~~~
def circulate():
   l=[10,20,30,40,50,60]
   n=(int(input()))
   
   print("After circulating the values are:",l[n:]+l[:n])
~~~
## Output:
![circulating](/pic.png)
## Result:
therefore circulating n variables using python program is sucessfull.