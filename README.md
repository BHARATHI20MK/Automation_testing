## Flipkart website testing

https://docs.google.com/document/d/1sUgMkvkawfEwy6i4ZqN_S5S-z5sU5Deo/edit?usp=sharing&ouid=117484597012560914610&rtpof=true&sd=true4


## EP testing

https://drive.google.com/file/d/1h0vg9qk6LE8M2VXDOJDNJEP_319jvnuq/view?usp=sharing

## Python problem 

Program 1: Binary number divisible by 5
```
numbers = input().split(",")
result = []
for num in numbers:
    decimal = int(num, 2)
    if decimal % 5 == 0:
        result.append(num)
print(",".join(result))
```
Program 2: No of alphabets and number 
```
text = input()
letters = 0
digits = 0
for ch in text:
    if ch.isalpha():
        letters += 1
    elif ch.isdigit():
        digits += 1
print("LETTERS", letters)
print("DIGITS", digits)
```
Program 3: Finding Factorial
```
num = int(input())
factorial = 1
for i in range(1, num + 1):
    factorial = factorial * i
print(factorial)
```


``
