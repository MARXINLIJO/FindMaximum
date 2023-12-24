# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:
''' 
# Program to mark the maximum of marks using the list method sort
# Developed by: MARXIN LIJO M
# RegisterNumber: 23013468
'''

# i)	To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: MARXIN LIJO M
RegisterNumber: 23013468
'''
def max_marks(m):
    #Write your code here
    m.sort()
    l=m[-1]
    return l
```
# ii)	 To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: MARXIN LIJO M
RegisterNumber: 23013468
'''
def max_marks(m):
    # write your code here
    l=max(m)
    return l
```
# iii) To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: MARXIN LIJO M
RegisterNumber: 23013468
'''
def max_marks(l):
    # write your code here
    m=l[0]
    for n in l:
        if(n>m):
         m=n
    return m
```
## Output:
![Screenshot 2023-12-24 213143](https://github.com/MARXINLIJO/FindMaximum/assets/145742540/fb749fd6-9409-4bdd-9f46-0b33f1d08ee8)
![Screenshot 2023-12-24 213153](https://github.com/MARXINLIJO/FindMaximum/assets/145742540/8e2917fd-2ddc-4369-8dae-d5c98a51f8fe)
![Screenshot 2023-12-24 213202](https://github.com/MARXINLIJO/FindMaximum/assets/145742540/4adbdbe2-3e34-4547-bd97-3b2354872eed)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
