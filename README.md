# split-string-and-remove-last-chara
## edit string from serial

a="M1   28.1i"

b=a.split( )    # split string 

c=b[1]

print(c[:-1])   # remove the last character


# 1 : 

M1   28.1i

# 2 : split

['M1', '28.1i']

28.1i

# 3 : remove the last character

28.1
