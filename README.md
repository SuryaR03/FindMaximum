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

i)	# To find the maximum of marks using the list method sort.

''' 
Program to mark the maximum of marks using the list method sort
Developed by: SURYA R
RegisterNumber: 23013019
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
    
ii)	# To find the maximum marks using the list method max().

''' 
Program to find the maximum marks using the list method max().
Developed by:SURYA R 
RegisterNumber: 23013019
'''
def max_marks(marks):
    large = max(marks)
    return large

iii) # To find the maximum marks without using builtin functions.

''' 
Program to the maximum marks without using builtin functions.
Developed by: SURYA R
RegisterNumber: 23013019
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max        

## Output:
![Screenshot 2023-12-21 154939](https://github.com/SuryaR03/FindMaximum/assets/147140237/fd147874-41d6-48d0-b123-2d130761fc35)
![Screenshot 2023-12-21 155412](https://github.com/SuryaR03/FindMaximum/assets/147140237/64f66e4d-b1a2-4614-abc5-abbbbf33d75a)
![Screenshot 2023-12-21 155444](https://github.com/SuryaR03/FindMaximum/assets/147140237/65bf3d44-d55d-4234-8eb1-57abdcee63b5)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
