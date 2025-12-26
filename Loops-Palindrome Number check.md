## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```num=int(input()) 

rev=0 

temp=num 

while temp>0: 

    rev=(10*rev)+temp%10 

    temp//=10 

    if rev==num: 

        print("The given number {} is a Palindrome".format(num)) 

    else: 

        print("The given number {} is not a palindrome".format(num))
```
## Output
<img width="741" height="136" alt="image" src="https://github.com/user-attachments/assets/df2fc54e-d2b8-4de1-9161-4229e9af8d28" />


## Result
Thus, the program has been successfully executed .
