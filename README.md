import os, random
os.system('cls')

Name =(input("Customer Name:"))#Rey Williams
Product =(input("Product:"))#Laptop
Quantity = int(input("Quantity:"))#2
Price= int(input("Price:"))#1000

if Quantity<1:
    print("Quantity must be more than 0")
elif Price<1:
    print("Price must be more then 0")
else:
    Total=Price*Quantity
    print(f'{Name} purchased {Quantity} {Product} for ${Total}')
    Continue=(input("Y/N:"))
    if Continue.lower()=="Y":
        Name=(input("Name:"))#Shane Williams
        Product=(input("Product"))#Keyboard
        Quantity=int(input("Price:"))#4
        Price=int(input("Price"))#40
        if Quantity<1:
            print("Quantity must be more then 0")
        elif Price<1:
            print("Price must be more then 0")
        else:
            Total=Price*Quantity
            print(f'{Name} purchased {Quantity} {Product} for ${Total}')



          





