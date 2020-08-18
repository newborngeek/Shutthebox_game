import random
from tkinter import *

"""
In this game you have to roll dices and close the numbers you've roll 
one or two numbers on the line from 1 to 9. It could be the sum of dices or 
the numbers on the dices
"""
root = Tk()
root.title('Shut The box')


#define function to roll dice
def dice():
    for i in range(1):
        dice1=random.randint(1, 6)
        dice1_label.config(text=dice1)
        dice2=random.randint(1, 6)
        dice2_label.config(text=dice2)

# function to cross out number
def cross_number_1():
    num1['text']='X'   

def cross_number_2():
    num2['text']='X' 

def cross_number_3():
    num3['text']='X'   

def cross_number_4():
    num4['text']='X'   
    
def cross_number_5():
    num5['text']='X'   

def cross_number_6():
    num6['text']='X' 

def cross_number_7():
    num7['text']='X'   

def cross_number_8():
    num8['text']='X' 
    
def cross_number_9():
    num9['text']='X' 

#reset button to restart the game
def reset():
    num1['text']='1'
    num2['text']='2'
    num3['text']='3'
    num4['text']='4'
    num5['text']='5'
    num6['text']='6'
    num7['text']='7'
    num8['text']='8'
    num9['text']='9'
    dice()


#recet button
reset = Button(root, text='Reset the game', command=reset)

# Roll dice button
roll_dice=Button(root, text='Roll the dice', command=dice)

# Numbers labels with function to be cosed
num1 = Button(root, padx=1, bg="papaya whip", width=3, text=" 1 ",font=('arial',20,'bold'),relief="sunken",bd=10, command=cross_number_1)
num2 = Button(root, padx=1, bg="papaya whip", width=3, text=" 2 ",font=('arial',20,'bold'),relief="sunken",bd=10, command=cross_number_2)
num3 = Button(root, padx=1, bg="papaya whip", width=3, text=" 3 ",font=('arial',20,'bold'),relief="sunken",bd=10, command=cross_number_3)
num4 = Button(root, padx=1, bg="papaya whip", width=3, text=" 4 ",font=('arial',20,'bold'),relief="sunken",bd=10, command=cross_number_4)
num5 = Button(root, padx=1, bg="papaya whip", width=3, text=" 5 ",font=('arial',20,'bold'),relief="sunken",bd=10, command=cross_number_5)
num6 = Button(root, padx=1, bg="papaya whip", width=3, text=" 6 ",font=('arial',20,'bold'),relief="sunken",bd=10, command=cross_number_6)
num7 = Button(root, padx=1, bg="papaya whip", width=3, text=" 7 ",font=('arial',20,'bold'),relief="sunken",bd=10, command=cross_number_7)
num8 = Button(root, padx=1, bg="papaya whip", width=3, text=" 8 ",font=('arial',20,'bold'),relief="sunken",bd=10, command=cross_number_8)
num9 = Button(root, padx=1, bg="papaya whip", width=3, text=" 9 ",font=('arial',20,'bold'),relief="sunken",bd=10, command=cross_number_9)

# Dice labels deffinition
dice1_label = Label(root, text='Dice 1', bg="blue", fg='white', font=('Comic Sans MS', 20), width=5)
dice2_label = Label(root, text='Dice 2', bg="blue", fg='white', font=('Comic Sans MS', 20), width=5)

# Adding labels and buttons to the main window
reset.pack(side=BOTTOM, anchor='s', padx=10, pady=10)
roll_dice.pack(side=BOTTOM, anchor='s', padx=10, pady=0)
dice1_label.pack(side=LEFT, padx=10)
dice2_label.pack(side=RIGHT, padx=10)
num1.pack(side=LEFT, anchor='n', pady=10)
num2.pack(side=LEFT, anchor='n', pady=10)
num3.pack(side=LEFT, anchor='n', pady=10)
num4.pack(side=LEFT, anchor='n', pady=10)
num5.pack(side=LEFT, anchor='n', pady=10)
num6.pack(side=LEFT, anchor='n', pady=10)
num7.pack(side=LEFT, anchor='n', pady=10)
num8.pack(side=LEFT, anchor='n', pady=10)
num9.pack(side=LEFT, anchor='n', pady=10)
# Window size
root.geometry('550x250')


root.mainloop()
