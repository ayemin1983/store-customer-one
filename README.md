import os, random
os.system('cls')

Name =(input("Customer Name:"))
Product =(input("Product:"))
Quantity = int(input("Quantity:"))
Price= int(input("Price:"))

if Quantity<1:
    print("Quantity must be more than 0")
elif Price<1:
    print("Price must be more then 0")
else:
    Total=Price*Quantity
    print(f'{Name} purchased {Quantity} {Product} for ${Total}')
    Continue=(input("Y/N:"))
    if Continue.lowe()=="Y":
        Name=(input("Name:"))
        Product=(input("Product"))
        Quantity=int(input("Price:"))
        if Quantity<1:
            print("Quantity must be more then 0")
        elif Price<1:
            print("Price must be more then 0")
        else:
            Total=Price*Quantity
            print(f'{Name} purchased {Quantity} {Product} for ${Total}')
          





