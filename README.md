# *🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values*
This Python program demonstrates how to sort a dictionary:
-> Alphabetically by keys
-> Alphabetically by values

_AIM:_
To write a Python program that sorts a dictionary's:
->Keys in alphabetical order
->Values in alphabetical order

_ALGORITHM:_

Start the program.
Define a dictionary with key-value pairs.
Sort by Keys:
Use sorted(dictionary.items())
Convert the result to a dictionary using dict()
Sort by Values:
Use sorted(dictionary.items(), key=lambda item: item[1])
Convert the result to a dictionary using dict()
Display the original and sorted dictionaries.
End the program.

_PROGRAM:_

<img width="763" height="182" alt="image" src="https://github.com/user-attachments/assets/9d6be0d6-0443-40fa-8117-7b895c683867" />

_OUTPUT:_

<img width="955" height="205" alt="image" src="https://github.com/user-attachments/assets/192c814d-2120-434d-83fa-67b1600d4d76" />

_RESULT:_
Thus , the program has been executed succesfully.

# *Dictionary Operations in Python: Merging Two Dictionaries*

_AIM:_
To write a Python program that merges two dictionaries and combines their key-value pairs.

_ALGORITHM:_

Define two dictionaries dict1 and dict2 with some key-value pairs.
Define a function merge() that merges the two dictionaries using the ** unpacking operator.
The merged result will combine keys from both dictionaries. If a key exists in both, the value from dict2 will overwrite that from dict1.
Call the merge() function and print the merged dictionary.

_PROGRAM:_

<img width="326" height="201" alt="image" src="https://github.com/user-attachments/assets/1650866b-874d-44d2-a1c1-0220cb4c7c1a" />

_OUTPUT:_

<img width="1038" height="248" alt="image" src="https://github.com/user-attachments/assets/0a8eef54-a0cb-4c02-bf04-6fd63511d783" />
<img width="846" height="267" alt="image" src="https://github.com/user-attachments/assets/4f6ef983-2f6d-46f4-b534-c1c11d0aad72" />

_RESULT:_
Thus , the program has been executed succesfully.

# *File Handling in Python: Count Lines Not Starting with 'T'*

_AIM:_
To write a Python program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T'.

_ALGORITHM:_

Open the file story.txt in read mode.
Initialize a counter count to zero.
Iterate through each line of the file:
Check if the first character of the line is not 'T'.
If the line does not start with 'T', increment the count by 1.
After processing all lines, print the count value, which represents the number of lines that do not start with 'T'.

_PROGRAM:_

<img width="640" height="286" alt="image" src="https://github.com/user-attachments/assets/af1b9ee9-52df-4a2a-a723-5943a44fe38d" />

_OUTPUT:_

<img width="977" height="236" alt="image" src="https://github.com/user-attachments/assets/503b3eb2-1eff-4281-9586-380f3f162661" />

_RESULT:_
Thus , the program has been executed succesfully.

# *Exception Handling in Python: Avoiding Index Errors*

_AIM:_
To write a Python program that handles an IndexError when trying to access an element beyond the available range of a list.

_ALGORITHM:_

Define a list list1 with some integer elements.
Use a try-except block:
In the try block, attempt to access an index that is out of range (e.g., list1[5]).
In the except block, catch the error and print a custom message "You're out of list range".
Print the result based on whether the index access succeeds or fails.

_PROGRAM:_

<img width="398" height="168" alt="image" src="https://github.com/user-attachments/assets/209f26fc-ab70-4850-920c-349b1cf85a59" />

_OUTPUT:_

<img width="558" height="135" alt="image" src="https://github.com/user-attachments/assets/44089fb0-c79e-4c28-81bc-433eaddbf56f" />

_RESULT:_
Thus , the program has been executed succesfully.

# *Classes and Objects in Python: Calculate the Area of a Circle*

_AIM:_
To write a Python program that calculates the area of a circle based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation.

_ALGORITHM:_

Get user input: Take the radius of the circle as input from the user.
Define the class: Create a class named cse.
Define the method: Inside the class, define the method mech to calculate the area of the circle using the formula:
Area = pi *r^2
Execute the program: Create an object of the class and call the method with the radius value.

_PROGRAM:_

<img width="564" height="203" alt="image" src="https://github.com/user-attachments/assets/3621b28e-a6f9-46a6-a0fd-519e10fe9c7b" />

_OUTPUT:_

<img width="787" height="246" alt="image" src="https://github.com/user-attachments/assets/26cf4b21-1e6b-480d-9e14-fdc3e7738b68" />

_RESULT:_
Thus , the program has been executed succesfully.
