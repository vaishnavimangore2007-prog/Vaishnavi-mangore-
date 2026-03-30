
# Vaishnavi 3
Assignment 3

int(input("enter first number:"))
b=int(input("enter second number:"))
c=int(input("enter third number:"))                                           


num = int(input("enter a number ")) 

if num % 2 == 0:
    print("even number")
else:
    print("odd number")



ch = input("Enter a character: ")

if ch.isalpha():            # 1. Removed space and fixed structure
    if ch.isupper():        # 2. Indented properly
        print("Uppercase letter")
    else:                   # 3. Indented to match 'if ch.isupper'
        print("Lowercase letter")
else:                       # 4. Indented to match 'if ch.isalpha'
    print("Not an alphabet")


---OUTPUT---

enter first number:10
enter second number:20
enter third number:30

enter a number 10
even number


Enter a character: v
Lowercase letter