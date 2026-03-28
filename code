# Password-Cracker code
import string

password = input("Enter your password: ")
chars = string.ascii_letters + string.digits + "!@#$%^&*()+-~"

cracked = ""
for p in password:
    for c in chars:
        if c==p:
            cracked+=c
            print(cracked)
            break
        print("Password Cracked ")
