# CafeMenuPython
📌 Project Overview

This is a simple Python program that shows a cafe menu, takes orders from the user, checks if the item is available, and calculates the total bill

📘 How the Program Works (Step by Step)

Create the Menu

menu={'Pizza':40,'Pasta':50,'Burger':60,'Salad':70,'Coffee':80}


Stores items and their prices in a dictionary.

Show Welcome Message & Menu

print("welcome to python restaurant")
print("Pizza: Rs40\n Pasta: Rs50 \nBurger: Rs60 \nSalad: Rs70 \nCoffee: Rs80")


Greets the user and displays the menu.

Initialize Total Bill

order_total=0


Sets the total bill to zero.

Take First Item Input

item_1=input("Enter the name of item you want to order=")


Asks the user to enter the first item.

Check First Item & Add to Total

if item_1 in menu:
    order_total+=menu[item_1]


If item exists, add its price to total.

Ask for Another Item

another_order=input("Do you wan to add another item ? (Yes/NO)")


Checks if the user wants to order a second item.

Take Second Item Input & Add to Total

if another_order=="Yes":
    item_2=input("Enter the name of second item=")
    if item_2 in menu:
        order_total+=menu[item_2]


Adds second item’s price if it exists.

Show Final Total

print(f"The total amount of item to pay is { order_total }")


Displays the total bill at the end.

✔ Summary

Menu stored in a dictionary.

User input for items.

Check if item is available.

Add price to total.

Display final bill.
