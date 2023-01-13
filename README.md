# Astitva-Yadav-Python-Project
a=input("DO YOU WANT TO START THE PROGRAM(Y/N): ")
while a=="Y"or a=="y":
    email=input("Enter your email: ").strip()
    username=email[:email.index("@")]
    domain_name=email[email.index("@")+1:]
    domain_name=domain_name.upper()
    format = (f" Your user name is '{username}' and your domain is '{domain_name}'")
    print(format)
    a=input("DO YOU WANT TO CONTINUE(Y/N): ")
print("THANK YOU VERY MUCH")
