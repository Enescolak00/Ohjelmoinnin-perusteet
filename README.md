A1_Tehtävä 1: 
print("Hello Python program")

A1_Tehtävä 2:
name1= "Jhon"
print(name1)
name2= "Harry"
print(name2)
print(name1, name2)
print(name1, "is eating ice cream with", name2)
print(name1, "and", name2, "are friends")

A1_Tehtävä 3:
Name = input("What is your name: ")
print("Hi there", Name)

A1_Tehtävä 4:
Num1 = 47
Num2 = 102
Sum = Num1 + Num2
Diff = Num2 - Num1 
Product = Sum * Diff
print(Num1, "+", Num2, "=", Diff)
print(Num2, "-",Num1, "=" ,Diff)
print(Sum, "*" ,Diff, "=" ,Product)
print("(",Num1,"+",Num2,") * (",Num2,"-",Num1,") =",Product)

A1_Tehtävä 5:
print("Calculate the area of a wall.")
Feed = input("Enter the width in meters:")
Width = int(Feed)
Feed = input("Enter the height in meters:")
Height = int(Feed)
FeedWidth = int(Feed)
FeedHeight = int(Feed)
print("Width is", Width, "m and height is", Height, "m.")
WidthHeightArea = FeedWidth + FeedHeight
print("The wall will be", WidthHeightArea, "square meters")


A1_Tehtävä 6:
Feed = input("Insert an integer: ")
Value = int(Feed)
FeedValue = int(Feed)
ValueRemainder = Value % 2
print("Value is", ValueRemainder)
print("The reimander is", ValueRemainder, "when", FeedValue, "is divided by 2" )

A1_Tehätävä 7:
print("calculate fuel consumption")
Feed = input("Enter travel distance (kilometer): ")
Distance = int(Feed)
Feed = input("Enter fuel usage(liters):")
FuelUsage = int(Feed)
Consumption = (FuelUsage/Distance) * 100
Consumption = int(Consumption)
print(f"Fuel Consumption is {Consumption} 1 per 100 km")

A2 tehtävä 1:
print("Program starting: ")
Name = input("What is your name: ")
First_number = input("Eneter a floating point number: ")
First_number = float(First_number)
Second_number = input("Enter second floating point number: ")
Second_number = float(Second_number)
print(f"{Name} you gave numbers {First_number} and {Second_number}")
Multi = First_number * Second_number
print(f"Multiplying frist and second number will result in product {round(Multi,2)}")
print("Program ending ")


A2 Tehtävä 2:
print("Program satarting. ")
Brand = input("Inseret car brand: ")
Model = input("Insert car model: ")
print(f"Car brand is \"{Brand}\"", end= "")
print(" and the model is", f"`{Model}´"),
print("Program ending. ")

A2 Tehtävä 3:
print("Program starting. ")
first_world = input("Inseret first word: ")
second_word = input("Inseret second_word: ")
print(f"1st word is {len(first_word)} characters long.")
print(f"2st word is {second_word}characters long.")
print(f"words together makes closed compound `{first_world}{second_word}´.")
print("Program ending. ")


A2 Tehtävä 4:
print("Program starting. ")
print("essimate how many minutes you spent on programming.")
Task_1 = int(input("A1_T1:"))
Task_2 = int(input("A1_T2:"))
Task_3 = int(input("A1_T3:"))
Task_4 = int(input("A1_T4:"))
Task_5 = int(input("A1_T5:"))
Task_6 = int(input("A1_T6:"))
Task_7 = int(input("A1_T7:"))
Total = Task_1+Task_2+Task_3+Task_4+Task_5+Task_6+Task_7
Average = float(Total / 7)
print(f"\nIn Total you spent {Total} minutes programming. ")
print(f"Average per Task was{round(Average,2)} min and same rounded to the neartes integer {round(Average)} min.")
print("Program ending")

A2 Tehtävä 7:
print("Program starting. ")
Fah = float(input("Inseret fahrenheits: "))
Celc = (Fah - 32) / 1.8
Celc = round(Celc, 1)
print(f"{Fah} °F is {Celc} °C")
print("Program ending")

A3 tehtävä 1:

print("Program starting.")
print("insert two integers: ")
int1 = int(input("Inseret first integer: "))
int2 = input("Inseret second integer: ")
if(int1 > int2):
    print("First intger is grater.")
elif(int1 > int2):
    print("Second integer is greater.")
else:
    print("Integers are same")
print("")
sum = int1 + int2
print(f"{int1} + {int2} = {sun}")
print("")
Reimander = Sum % 2
if(Reimander == 0):
    print("Sun is even.")
else:
    print("Sun is odd.")
print("Program ending")


A3 Tehtävä 2:

print("Progmram starting. ")
print("String comparisons")
Word1 = input("Inseret first word:")
Char = input("Inseret a character: ")
if(Char in Word 1):
    print(f"Word1 \"{Word1}\"contains character \"{Char}\"")
else:
    print(f"Word \"{Word1}\"does not contain charakter \"{Char}\" ")
Word2 = input("Inseret second word: ")
if("Word1 < Word2"):
    print(f"The first word \"{Word1}\"is before the second word\"{Word2}\ alphabetically.")
elif(Word2 < Word1):
    print(f"The second word \"{Word2}\"is before the first word\"{Word1}\ alphabetically.")
else:
    print("Both inserted words are the same alphabetically, "{Wordfirst}"")
print("Program ending. ")

A3 Thetävä 3
print("Program starting. ")
print("This is a program with simple menu, where you can choose which operation the program performs.")
Name = input("Before the menu, please inseret your name: ")
print("")
print("Options")
print("1 - print welcome message")
print("0 - Exit")
choise = int(input("Your choices: "))
if ( Choise == 1):
    print(f"Welocome {Name}!")
elif(Choise == 0):
    print("Exiting...")
else:
    print("Unknow option")

print("program ending")

A3 Tehtävä 4:


A3 Tehtävä 6:

print("Program starting. ")
print("Welcome to the unit conveter program! ")
print("Follow the menu instruction below\n")

print("Options:")
print("1 - Lenght")
print("2 - Weight")
print("0 - Exit")
choise = int(input("Your choice: "))

if(choice == 1):
    print("\nlength options:")
    print("1 - Meters to kilometers")
    print("2 - kilometers to meters")
    print("0 - Exit")
    choice2 = int(input("Your choice: "))
    if choice2 == 1: 
       meters = float(input("Inseret meters: "))
       kilometers = meters / 1000
       print(f"{meters: 1f} m is {kilometers: 1f} km")
    elif choice2 == 2:
       kilometers = float(input("Inseret kilometers: "))
       meters = kilometers * 1000
       print(f"{kilometers: 1f} km is {meters: 1f} m")
    elif choice2 == 0:
       print("Exiting...")
    else:
       print("Unknow option.")
elif(choice == 2):
       print("Weight opitions:")
       print("1 - Grams to pounds")
       print("2 - Pounds to grams")
       print("0 - Exit")
       choice2 = int(input("Your choice: "))
     if choice2 == 1: 
        grams = float(input("Inseret grams: "))
        pounds = grams * 0.00220462
        print(f"{pounds: 1f} g is {grams: 1f} 1b")
     elif choice2 == 1:
    puonds = float(input("Inseret pounds: "))
    grams = pounds / 0.00220462
    print(f"{pounds: .1f} 1b is {grams:.1f} g")
elif choice2 == 0:
print("Exiting ...")
else: 
print("Unknown option.")
elif choice == 0:
print("Exiting...")
print("Program ending.")

A3 Tehtävä 7:
print("Program starting.")
print("Testing decision structures.")
Feed = input("Inseret an integer:")
Value = int(Feed)
print("Options:")
print("1 = In one multi branched desicion")
print("2 = In multiple independent if-statamentes")
print("0 = Exit")
Feed = input("Your choice:")
Choice = int(Feed)
if(Choice == 1):
   print("Using one multi branched desicion structure.")
   if(Value >= 400):
        Value += 44 
   elif(Value >= 200):
       Value += 22
   elif(Value >= 100):
     Value +=11
   print(f"Results is {Value}")       
elif(Choice == 2):
   if(Value >= 400):
        Value = Value + 44 
   if(Value >= 200):
      Value = Value + 22
   if(Value > 100):
    Value = Value + 11
   print(f"Resolt is {Value}")    
elif(Choice == 0):
    print("Exiting...")
else:
    print("Unknow option")
print("")
print("Program ending.")

