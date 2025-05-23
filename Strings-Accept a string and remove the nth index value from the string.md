#Strings-Remove Nth Index Character from a String
## Aim
To write a Python program that accepts a string and removes the character at a specified index.
## Algorithm
1. Define a function named remove that takes a string s as an input argument.
2. Initialize an empty string a to build the modified version of the input string.
3. Use a for loop to iterate over each index i of the input string.
4. In each iteration, check if the current index i is not equal to 3.
5. If i != 3, append the character at index i to the string a.
6. If i == 3, skip appending (effectively removing the 3rd index character).
7. After the loop ends, return the new string a.
8. Call the function and print the result.
## Program
```
def remove(s):
    new_string = s[:3] +s[4:]
    print(new_string)
```
## Output
![image](https://github.com/user-attachments/assets/23c67dfc-fdfe-45b9-895a-1013cba1423f)
## Result
Thus the program that accepts a string and removes the character at a specified index has been executed successfully.
