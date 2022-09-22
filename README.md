# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Give a user defined function as def circulate()
### Step 2: 
Give the value from the user for the number of rotation
### Step 3: 
Give a list with an array of certain numbers
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the value
### Step 6: 
End the programm
## Program:
```python
#Program to circulate N values.
#Developed by:ALAGU NACHIYAR K 
#RegisterNumber:22002084
def circulate():
    a=eval(input())
    n=int(input())
    a=a[n:]+a[:n]
    print('After circulating the values are: {}'.format(a))
```


## Output:
![WhatsApp Image 2022-09-19 at 10 57 52 AM](https://user-images.githubusercontent.com/113497340/190954611-cc756dd0-177a-4969-9594-a4aa6c46793b.jpeg)

## Result:
Thus the circulate n variables are successfully executed
