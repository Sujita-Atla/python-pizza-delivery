# python-pizza-delivery
print("Welcome to Python Pizza Deliveries!")
size = input("What size pizza do you want? S, M or L: ")
pepperoni = input("Do you want pepperoni on your pizza? Y or N: ")
extra_cheese = input("Do you want extra cheese? Y or N: ")
bill = 0
if size == "s":
    bill += 15
    print(f"Your bill is {bill}")
elif size == "m":
    bill += 20
    print(f"Your bill is {bill}")
elif size == "l":
    bill += 25
    print(f"Your bill is {bill}")
else:
    print("Give correct input")
if pepperoni == "y":
    if size == "s":
        bill += 2
    else:
        bill += 3
print(f"Your final bill is {bill}")
