# Fruit-Guessing-Game
by using this code you can play Fruit Guessing game
import random
user_name=input("Enter the your name ")
print('-'*10,f"Welocome {user_name} Ji in Fruit Guess Game ",'-'*10)
Fruits=['Apple','Watermelon','Orange','Pear','Cherry','Strawberry','Nectarine','Grape','Mango','Blueberry',
        'Pomegranate','Carambola','Plum','Banana','Raspberry','Mandarin','Jackfruit','Papaya',
'Kiwi','Pineapple','Lime','Lemon','Apricot','Grapefruit','Melon','Coconut','Avocado','Peach'
]
print(Fruits)
print('-'*10,"You Can Chosse Fruit name in the given list",'-'*10)
print('*'*10,"If you want to quit then type '999' at the Enter the Fruit",'*'*10)


  
while True:
    Fruit_name=input("Enter the your Fruits Please :")
    A=random.choice(Fruits)
    if '999'==Fruit_name:
        print(f"your Potential is too Low {user_name} to playing this game ")
        break
    elif Fruit_name == A :
        print("Your number Chossed Correct Fruit ")
        break
    else:
        print("you enter wrong Fruit or invalid input")
        print(A)
print(f"Thanks For Playing Game {user_name}")
