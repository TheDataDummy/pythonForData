# Python for Data Analysis \[FULL COURSE\]
A free resource for total beginners to learn python with a specific focus on data analysis and other data tasks


## Prerequisites
Our one and only prerequisite is Python, of course!  We will be using the open source anaconda distribution which is very common in data circles as it includes some useful tools and packages commonly used when working with data.  Check out the link below to go to the Anaconda site and download/install the Anaconda service for your machine type (mac or windows).
#### [Link to Anaconda (as of August 2025)](https://www.anaconda.com/download/success)

## Environment setup
So, you've got Anaconda installed, great!  From here, if you're on windows, we want to open the new Anaconda Prompt program that it installed and issue some commands to set up our workspace to get started.  On mac you can just issue commands from the terminal.

First, we'll want to set up an <b>environment</b> to do our work in.  Since we're using Anaconda for this course, we'll be using the environment manager that comes with it, Conda.  In order to create a conda environment and activate it, run the following commands in the Anaconda Prompt  

- `conda create --name dataEnv`

- `conda activate dataEnv`


This will create a new environment for us to work in.  We'll touch on why environments are important in a little bit, but for now, let's get Jupyter up and running!  

Jupyter is the software that we will be using to write and execute our Python code.  In order to start Jupyter, in the Anaconda Prompt (windows) or in the Terminal (Mac) enter the following commnand: 

`jupyter Lab`

Jupyter will open in your web browser, and from here, we are good to start coding!

You can continue on to the first section of the course by opening the file titled: <b>"part1Introduction.ipynb"</b>