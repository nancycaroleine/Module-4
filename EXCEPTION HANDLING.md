# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

1. Begin the program.  
2. Read a string `input_str` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list of grades.  
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.  
5. If the conversion is successful, print the list `l1` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.  
7. Terminate the program.

---

### PROGRAM

```
Reg.No:212223060181
Name:NANCY CAROLEINE P R

try:
    a = input()
    b = input()
    if a.isdigit() and b.isdigit():
        print(int(a) + int(b)) 
    else:
        raise TypeError
except TypeError:
    print("cannot add integer with string")

```

### OUTPUT

<img width="833" height="395" alt="image" src="https://github.com/user-attachments/assets/9790b61c-39a4-4794-b51c-d6e5ffa86d12" />

### RESULT

Thus, the python code is written and executed successfully.
