## Welcome to Python4Kids

You can use the [editor on GitHub](https://github.com/carbonjo/Python4Kids/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

## Assignment
Take material from Runestone and create lessons -- Joaquin: Chapter 1. Anne: Chapter 5.


## Python code

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

## Chapter 5


(This goes after my first piece of chapter 5.)

Next skip to this block of code below in chapter 5.5. We should change the loop variable to side instead of _ if possible. Also, in any of the lessons, better to have descriptive variable names for kids, even if they are longer. Also, they'll do better with snake_case than camelCase.

Show this code and ask them what they think is happening. Then explain the loop. 

'''python
import turtle
wn = turtle.Screen()

elan = turtle.Turtle()

distance = 50
for _ in range(10):
    elan.forward(distance)
    elan.right(90)
    distance = distance + 10
'''
At this point, I might give them time to play for 10 minutes and then show their creations. Is there an easy way to show their creations to the class? 

Suggestions can be to use some functions on the cheat sheet, like the colors, pensize, distance addition.
Quicker kids can be challenged to make other polygon spirals and even to make multiple spirals using a for loop and goto etc.

A few minutes into their artwork, I would stop them and just show them the first block in section 5.6.

'''python
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
'''

We could also show some things like the sierpinski triangle after this. 


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/carbonjo/Python4Kids/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
