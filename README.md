# Password
#You can create a random password
#For generating a random we can use the below code

import random
len = int(input("enter the length of password"))
a="abcdefghijklmnopqrstuvwxyz01234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ!@#$%^&*()?"
b = "".join(random.sample(a,len ))
print(b)
