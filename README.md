# turtle
using turtle in python
 ```
 import turtle 

t = turtle.Turtle()
s = turtle.getscreen()
t.ht()
length = 100
small = 65
big = 115
t.speed(100)

for i in range(100):
    t.forward(length)
    t.right(small)
    t.forward(length)
    t.right(big)
    t.forward(length)
    t.right(small)
    t.forward(length*2)
    t.left(small)
    t.forward(length)
    t.left(big)
    t.forward(length)
    t.left(small)
    t.forward(length)
    t.right(36) #  do 360/ how many corners you want on the outside of your shape to fill in the brackets
