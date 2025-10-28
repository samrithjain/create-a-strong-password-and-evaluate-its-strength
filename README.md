# create-a-strong-password-and-evaluate-its-strength
cyber security internship at elevate labs
# Task-6-Create-a-Strong-Password-and-Evaluate-Its-Strength
Cyber Security

# Create a Strong Password

It means combination of upper case,lower case,special characters and numbers.Then length of password should be morethan eight characters.

For example : harigat@02    guruwee@20      hiiii@02

Note : Not try use your name with bate of brith combination(or) if you use try hide your bate of brith in social media platfrom.Like bio(or)frist cry etc.

# Python password checker

In this process,I used entropy values of characters to check password strength.

          entropy = length_password * log2(characters_of_password)
          
I started with upper case values,lower case values,special character values and numbers.

Like lower_case="abcdefghijgklmnopqrstuvwxyz"    Like upper_case="........."    number="0123....."    special="!#$%*....."

length_password=len("enter of password")

log2(lower_case values+upper_case value+number+special)

Example: password123456 entropy is 82.33

# Password Strength Checker

The password strength checker are lots tools are available in online.We used like 

          www.passwordmonster.com
          www.bitwarden.com
          
In this two online tools our password strength will checks.

# How to strong our password

1.Combinations of upper_case,lower_case,special and numbers.

2.Try to not use your names and bate of brith in passwords(or) Hide your bate of brith.

3.Password value is atleast 12 characters.

4.Change(or)update your passwords with period of time.Avoid login(or)signup untrust websites(or)pages.

# Brute force & Dictionary

Brute force attack is a systematically tries all possible combinations of characters (letters, numbers, symbols) until the correct password is found.

Example : name : sai kumar

Attack start with saikumar@12  sai@kumar SaiKumar@33 ....

A dictionary attack uses a precompiled list of common passwords or phrases.It means comman passwords(or)leaked passwords and default passwords.

Example : password@123    123456789    loveyou@143   ....
