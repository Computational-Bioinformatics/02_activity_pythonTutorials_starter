# Bioinformatics (CMPSC 300) Activity 2

This repository contains information about Bioinformatics activity 2 deliverables. This assignment invites students to follow a tutorial to investigate BioPython and to write code to run experiments.

## Dates

Handed out: 16 Sept 2022

Due: 16 Sept 2022

## Objectives

- To follow a tutorial to learn the coded techniques behind simple bioinformatics experiments.
- To adapt the code for an original experiment.
- To interpret the results from a simple experiment.

## Introduction

In Bioinformatics research, investigators often find it necessary to write their own programs or tools using computer programming to complete projects in research. Before each coding task, the investigator may spend time to research methods, choose algorithms and study the details of a working solution. In this acitivity, you will gain some experience in looking into how some programming techniques apply themselves to research in Bioinformatics.

In this activity, you will follow tutorials of Python programming at __Python for Biologists__ at [https://www.pythonforbiologists.org/](https://www.pythonforbiologists.org/) and BioPython [http://biopython.org/DIST/docs/tutorial/Tutorial.html](http://biopython.org/DIST/docs/tutorial/Tutorial.html).

At both or these websites, you will find a host of information about how to comlpete commonly used automations that are necessary when working with data in the contect of a bioinformatics experiment.

For example, on this tutorial, you will find  lessons for working with data types, utilizing conditional statements, creating utilities for completing smaller tasks, implementing iterations with loops and many commonly used tasks. A variety of samples of code is given in for many uses. It should be said that many of the tools that are developed for research often include several of these techniques working together to complete tasks.

As you take the tutorial's code from the examples to add to your own script, please provide documentation in the form of comments for important lines and code blocks to describe what is happening at the current step. In your code, you can add these comments using the `#` character on the left of the line to be ignored by Python.

## Part 1: The Python for Biologists Tutorial

You are to choose two of the short tutorials at the _Python for Biologists_ website. Using the tutorial, you are to follow the code and prepare a script file to run the code.

Your work for each introduced code will resemble the following.

``` python
# Code to ask the use what her favorite color is and store the response as a string in the variable, facColor_str.

# Ask user for color, save it as variable favColor_str
favColor_str = input("What is your favorite color")

# Print out the color with a charming and heart-felt message.
print(f"Your favorite color is : {favColor_str}")
```

## Part 2: The BioPython Tutorial

In the Biopython tutorial, there are lots of amazing examples of completing more tasks with the use of the Biopython library. In this part, you are to explore the code of two different examples. You will add this code to your script file to introduce it to the reader. Please be sure to provide sufficient documentation to describe the goals of the examples, and also to describe what each line is doing in the code.

## Running Your Code

Add all your code in to the provided script file which automatically includes the commonly used libraries for BioPython.

Please note you may have to include other libraries in your script file to run the code. _If this is the case, please add these libraries to your script and then test that the script executes accordingly!_

For the included script file, `demoProgram.py` can be executed using the following command at the terminal.

```
python demoProgram.py
```

## Reflection

Once your code cahas been completed from both tutorials, you are to respond to the questions of the `writing/reflection.md`. Please be sure that you use Markdown where necessary for formatting.

## Assessment
This is a checkmark grade.

## GatorGrade

You can check the baseline writing and commit requirements for this lab assignment by running department's assignment checking `gatorgrade` tool. To use `gatorgrade`, you first need to make sure you have Python3 installed (type `python --version` to check). If you do not have Python installed, please see:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [How to Install Python 3 and Set Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Then, if you have not done so already, you need to install `gatorgrade`:

- First, [install `pipx`](https://pypa.github.io/pipx/installation/)
- Then, install `gatorgrade` with `pipx install gatorgrade`

Finally, you can run `gatorgrade`:

`gatorgrade --config config/gatorgrade.yml`