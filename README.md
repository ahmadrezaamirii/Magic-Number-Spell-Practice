# Magic-Number-Spell-Practice
---
In the land of wizards, there is an old spell that says that every magic number must have a special property:

If a number is divisible by 3, it is considered a magic number.

If a number is divisible by 5, it is considered a cursed number.

If a number is both magic and cursed, it is considered a legendary number.

Otherwise, it is a regular number.

Your task: Write a program that takes an integer as input and determines whether it is a magic, cursed, legendary, or regular number.

Make sure that the words in quotation marks are displayed exactly as the output.

Input:

An integer n

Output:

If n is divisible by 3, print: "magical"
If n is divisible by 5, print: "cursed"
If n is divisible by both, print: "legendary"
Otherwise, print: "normal"
***
Input :
``
x = int(input("Enter your number: "))
``

Use " if " :

````
if x % 3 == 0 and x % 5 == 0 :
    print('Legendary')
elif x % 3 == 0 :
    print('Magical')
elif x % 5 == 0 :
     print('Cursed')   
else :
     print('Normal')
````     
***
[My GitHub profile](https://github.com/ahmadrezaamirii)

[My LinkedIn](https://www.linkedin.com/in/ahmadreza-amiri-46936b1b2/)
