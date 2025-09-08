## NAME: SUDHAKAR K
## REGNO: 212222240107

# Experiment-7
## Write a python program for sorting and inspect for failures. 
## Algorithm:
1. Start the program.

2. Get the number of elements from user

3. Get the elements to be sorted

4. Traverse the array and sort the elements one by one

5. Print the sorted array

6. Stop the program. 

# Program:
```python
n = int(input("Enter the number of elements: "))
arr = []
try:
    for i in range(n):
        a = int(input("Enter the element: "))
        arr.append(a)
    for i in range(n):
        for j in range(i + 1, n):
            if arr[i] > arr[j]:
                arr[i], arr[j] = arr[j], arr[i]

    print("The array after sorting:")
    for i in range(n):
        print(arr[i], end=' ')

except ValueError:
    print("Enter a valid number.")
```
# Output

![image](https://github.com/user-attachments/assets/572d7d10-8fc6-45a9-9d62-8dd37e00cdbb)

![image](https://github.com/user-attachments/assets/e74aaaed-3984-423d-af5e-bed15b2b8202)

![image](https://github.com/user-attachments/assets/d24ea534-894f-4a63-8ebd-599a3864c75c)

![image](https://github.com/user-attachments/assets/1c2f0cc3-8dfb-49b9-8941-41028639c454)


# Result
Thus, a program to check sorting has been written and test cases have been written and verified 
successfully.
