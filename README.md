# EXPERIMENT-6
## AIM:To write a Python program for checking Palindrome and to write test cases for ir. 

## ALGORITHM
Step 1: Start
Step 2: Get an input from the user by prompting
Step 3: Run a loop form 0 to len/2.
Step 4: Check if the characters are the same both from the start and the end till len/2.
Step 5: If it is, return the result that it is a palindrome.
Step 6: Else, return that it is not a palindrome.
Step 7: Stop. 

## PROGRAM
```
def Palindrome(string):
    for i in range(0, int(len(string) / 2)):
        if string[i] != string[len(string) - i - 1]:  
            return False
    return True
s = input("Enter a string: ") 
c = 1
for i in s:
    if not i.isalpha():
        c = 0
        break  
if c == 0:
    print("Enter a valid string")
    print("Test Case:Fail")
else:
    answer = Palindrome(s)
    if answer:
        print("The given string is a palindrome")
        print("Test Case:Pass")
    else:
        print("The given string is not a palindrome")
        print("Test Case:Pass") 
```

## OUTPUT
<img width="301" height="66" alt="image" src="https://github.com/user-attachments/assets/4de15a91-5804-4961-ad6d-311379230e24" />
<img width="326" height="68" alt="image" src="https://github.com/user-attachments/assets/5c0e52b8-7879-46cc-8a9d-1067045f3ec1" />
<img width="348" height="73" alt="image" src="https://github.com/user-attachments/assets/e32ad810-1a44-40c5-88cd-d42e0d583c65" />
<img width="319" height="73" alt="image" src="https://github.com/user-attachments/assets/d8e36866-cdbc-49de-860c-1212d6a0083d" />
<img width="375" height="75" alt="image" src="https://github.com/user-attachments/assets/b075bb25-3d72-4d54-b425-af6508b62965" />


## RESULT
Thus, the Python program for checking Palindrome and to write test cases for ir is executed successfully.
