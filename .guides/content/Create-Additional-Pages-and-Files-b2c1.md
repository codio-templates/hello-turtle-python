---
Instruction through Codio is built around the guides feature. This is a brief description on how the demo on the previous page was built. Please see the [**documentation**](https://docs.codio.com/authoring.html) for more information about content authoring with guides.

### Build on this Starter Pack
---
Please note that there is software, files, scripts, etc. preconfigured in this **Hello Turtle in Python** Starter Pack that allow for use of turtle in Python.   

* `bg.sh` file is a Bash script in the `.guides` folder that allows for efficient operations on multiple files in the command line. 
* `X server` is software downloaded to allow for the functionality of the preview in panel 1.
* `turtle.cfg` contains the coordinates for the starting location of the turtle window in the pane.

Follow the directions below to build out this project with your own activities in turtle:

### Code Editor File
---
Add a `.py` file to this project. This is the file students will edit. Right-click on the name of your project or book in the directory tree on the left. Select `New File...` and then type its name and file extension. Copy and paste the following template code into the new file.

```
import turtle

# All of your turtle commands

# go in this space here

turtle.mainloop()
```

### Page Layout
---
Each page in the guide can have its own layout. You can select how many panels you want, and what information goes in each panel. Click the wrench in the top-right corner of your guide. When setting up Turtle Graphics:
* Under **Page**, select either *3 columns* or *3 panels* with or without a tree.
* Under **Open Tabs** drag in your `.py` file and position it in panel 0. 
* Press the **Add Tab** button and specifiy the type as **Preview.** Paste the following in the URL field: `https://{{domain3050}}/`. Position it in panel 1. 

![Open Tabs](.guides/img/opentabslayout.png)

### Try It Button
---
|||
Use the following markdown syntax when creating the `Try It` button:

```markdown
{Try it}(bash .guides/bg.sh python3 filename.py)
```
|||

### Add this Project to a Course
---
You can add this project as an assignment to an existing course:

1. In the course module, click **Add Assignment**.
2. On the Create Assignment page, click **Project based**.
3. To import a project, click the **Click here** link under **Starting Point.** 
4. Click **Copy Project** and browse to the project and select it.
5. Click **Create.**
6. **Publish** the assignment so that it can be viewed by students in your course.