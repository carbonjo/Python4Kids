## Welcome to Python4Kids



## Chapter 1 (1 hours)

1.1 Algorithms
[How to make PBJ sandwich](https://www.youtube.com/watch?v=RjHzD2sfWcQ)

1.3 What is Python

1.4 How to run Python on the textbook.

1.5 practice

1.6 Natural and Formal languages

1.7

1.8

1.9

1.10

1.11

1.12

skip project 1.13

## Chapter 5

### Activity
Show this turtle code and ask kids about what it does. Have them try it in Runestone chapter 5 and ask them to try to alter it to make a square.

```python
import turtle

my_turtle = turtle.Turtle()   # create a turtle
my_turtle.color('green')      # set the color
my_turtle.forward(50)         # draw a green line of length 50
my_turtle.up()                # lift up the tail
my_turtle.forward(50)          # move forward 50 without drawing
my_turtle.right(90)           # change direction to the right, left works too
my_turtle.down()              # put the tail down
my_turtle.backward(100)       # draw a green line 100 units long
```

In the sandbox, show kids how to add a bgcolor, pencolor and pensize for their square. Maybe have a cheat sheet with a few commands and color strings?


Show next code block from Chapter 5. Ask kids what they think each line does. Ask them to modify to draw a triangle, or for a challenge, the letter A, their choice.

```python
import turtle

wn = turtle.Screen()
wn.bgcolor("lightgreen")        # set the window background color

tess = turtle.Turtle()
tess.color("blue")              # make tess blue
tess.pensize(3)                 # set the width of her pen

tess.forward(50)
tess.left(120)
tess.forward(50)

wn.exitonclick()  
```
Have the kids run through the rest of this page if they finish before others. 



(This goes after my first piece of chapter 5.)

Next skip to this block of code below in chapter 5.5. We should change the loop variable to side instead of _ if possible. Also, in any of the lessons, better to have descriptive variable names for kids, even if they are longer. Also, they'll do better with snake_case than camelCase.

Show this code and ask them what they think is happening. Then explain the loop. 

```python
import turtle
wn = turtle.Screen()

elan = turtle.Turtle()

distance = 50
for _ in range(10):
    elan.forward(distance)
    elan.right(90)
    distance = distance + 10
```
At this point, I might give them time to play for 10 minutes and then show their creations. Is there an easy way to show their creations to the class? 

Suggestions can be to use some functions on the cheat sheet, like the colors, pensize, distance addition.
Quicker kids can be challenged to make other polygon spirals and even to make multiple spirals using a for loop and goto etc.

A few minutes into their artwork, I would stop them and just show them the first block in section 5.6.

```python
import turtle
wn = turtle.Screen()
wn.bgcolor("lightgreen")
tess = turtle.Turtle()
tess.color("blue")
tess.shape("turtle")

dist = 5
tess.up()                     # this is new
for _ in range(30):    # start with size = 5 and grow by 2
    tess.stamp()                # leave an impression on the canvas
    tess.forward(dist)          # move tess along
    tess.right(24)              # and turn her
    dist = dist + 2
wn.exitonclick()
```

We could also show some things like the sierpinski triangle after this. 

### Example
A colorful drawing of the Siepinski Triangle done with turtle code: [click here](Sierpinski.md)


