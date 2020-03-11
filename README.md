# shapes-
import turtle # this allows you to draw 

s = turtle.Turtle()
s.penup()
s.setposition(250, 300)
s.pendown()
s.forward(50)
s.right(90)     

s.forward(50)
s.right(90)

s.forward(50)
s.right(90)

s.forward(50)
s.right(90)
s.fillcolor("blue")

turtle.done()

poly= turtle.Turtle()

poly.penup()
poly.setposition(-250, 250)
poly.pendown()
poly.circle(50)
poly.penup()
turtle.done()

Tri = turtle.Turtle()
Tri.penup()
Tri.setposition(250, -300)
Tri.pendown()
Tri.forward(100)
Tri.right(90)
Tri.forward(100)
Tri.setposition(250, -300)
Tri.penup()
turtle.done()

pen = turtle.Turtle()
pen.penup()
pen.setposition(-190, -190)
for i in range(5):
  pen.pendown()
  pen.forward(50)
  pen.right(72)
  pen.penup()
turtle.done()
