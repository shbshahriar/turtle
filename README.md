# sun-turtle
# This is a turtle project which i created for at the begining of my python programming career

# first of all need to import the turtle module
import turtle
#then name the turtele function
sun = turtle.Turtle()
# set the color and speed

sun.color("red","yellow")
sun.speed(0)
#use fill to color fill
sun.begin_fill()

# use for loop to make that easy
for i in range(48):
    sun.forward(300)
    sun.left(169)
sun.end_fill()

# hide the turtle to make clean
sun.hideturtle()
turtle.done()
