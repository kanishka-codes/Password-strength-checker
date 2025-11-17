##Password Strength Checker in C

This project is a simple C program that analyzes a user-entered password and classifies it as:
Strong

Medium

Weak

The classification is based on the presence of:

Uppercase letters

Lowercase letters

Digits

Special characters

Minimum required length

##Features

✔ Reads a password from the user
✔ Checks password length
✔ Counts uppercase, lowercase, digits, and special characters
✔ Classifies the password as Strong / Medium / Weak
✔ Displays a detailed breakdown of password composition

##How It Works

The program scans each character of the password using a for loop and increments counters accordingly:

uc → uppercase count

lc → lowercase count

dg → digit count

sp → special character count

Then it checks:

Strong Password

At least 8 characters

Contains 1 uppercase

Contains 1 lowercase

Contains 1 digit

Contains 1 special character

Medium Password

At least 6 characters

Contains all character types (uppercase, lowercase, digit, special)

Weak Password

Anything failing the above rules

##Sample Output

Enter Your password: Abc@1234 

Your password is strong

Your password length is:8

Your password contain digit:2

Your password conatin upercase:1 and lowercase:3

your password conatins special character:1

You can go for this password.


##How to Run

Save the file as password_checker.c

Compile the program and run.

##Author

Kanishka Jain