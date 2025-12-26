# Number-of-digits
s = input("Input a string: ")
d = l = 0

for c in s:
    if c.isdigit():
        d = d + 1
    elif c.isalpha():
        l = l + 1
    else:
        pass

print("Letters", l)
print("Digits", d)

output:
Input a string: a123
Letters 1
Digits 3
