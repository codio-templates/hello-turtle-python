---
Turtle Graphics allows students to create graphical output with the Turtle Graphics library. Like a pencil on paper, the Turtle object leaves a line as it moves around the screen. 

<iframe src="https://giphy.com/embed/0rjdTDCRlkf0SAiAXZ" width="300" height="250" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/0rjdTDCRlkf0SAiAXZ"></a></p>

### Turtle Syntax
---
Turtle is pre-installed in the Python library. You need to `import turtle` library as the first line of your code and end your code by calling `mainloop()`. The next step is to create a turtle object to move around the screen.

```python
import turtle

t = turtle.Turtle() # create a turtle called t

# All of your turtle commands
# go in this space here.

turtle.mainloop()
```

Here are some basic commands to use with the turtle library:

|Command|Parameter|Description|
|:-----:|:-------:|:---------:|
|`t.forward(n)`|Where `n` represents the number of pixels|Move the turtle forward|
|`t.backward(n)`|Where `n` represents the number of pixels|Move the turtle backward|
|`t.rt(d)`|Where `d` represents the number of degrees|Turn the turtle to the right|
|`t.lt(d)`|Where `d` represents the number of degrees|Turn the turtle to the left|

### Turtle Commands
---
++**Sample Code:**++ 
Let's try this very simple command below. **Copy and paste** the following code in the editor on the left. Python style guidelines call for four spaces per indentation level. Click the `TRY IT` button to see the graphical output.

```python
for i in range(4):
	t.forward(100)
	t.left(90)
```
Close the window with the turtle output to stop your program.

{Try it}(bash .guides/bg.sh python3 turtle1.py)

### Customize Your Turtle
---
The following table provides additional commands you can use to customize your Turtle.

|Command|Parameter|Examples|
|:-----:|:-------:|:---------:|
|`t.color('color')`|Where [**color**]("https://www.w3schools.com/colors/colors_names.asp") represents the track or line color you want tina to leave behind|red, orange, yellow, green, blue, purple|
|`t.shape('turtle')`|Where `SHAPE` represents the shape the turtle takes|turtle, circle, square, arrow, classic or triangle|
|`t.speed(s)`|Where `s` represents how many milliseconds it takes the turtle to perform an action|1 (fastest) through 10 (slowest)|
|`t.pensize(s)`|Where `s` represents the width of the pen| must take a positive number|