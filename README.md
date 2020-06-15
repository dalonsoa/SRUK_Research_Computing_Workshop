[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dalonsoa/SRUK_Research_Computing_Workshop/master)

# About the Workshop

Welcome to this second event of the SRUK Research Computing Workshop series, devoted to Python. Python is programming language that has become one of the dominant tools in research and teaching thanks to its flexibility, simplicity, and enormous supporting community. Specifically, this hands-on workshop will cover the following content:

- Brief introduction to the basics
- Overview of Python packages and developing your own libraries
- Numerical computation with [Numpy](https://numpy.org/) and [Scipy](https://www.scipy.org/)
- Data science with [Pandas](https://pandas.pydata.org/)
- Professional-looking figures with [Matplotlib](https://matplotlib.org/)

This workshop is at a beginners-intermediate level. Although there will be an introduction to basic Python, we will not linger over it for too long and will move soon to more advanced – and useful – stuff. Even though we will not go through very complicated examples, you are more than welcome to go through some basic Python concepts on your own prior to the workshop (e.g., check the first half of the content provided [here](https://imperialcollegelondon.github.io/python-novice-mix/)) and get the most out of this training!

Join this event if you want to…

- Create your own libraries of recurrent functions and tools you will be using to analyse your data.
- Analyse your data, fitting it to complex functions using powerful algorithms or exploring their statistical properties.
- Learn how to easily generate publication-quality figures.

If time allows, at the end of the workshop we will provide tips and resources for those wanting to expand their knowledge on other topics such as differential equation solving, parallel computing, machine learning, and deep learning.

# Setting up the environment

The aim of this workshop is to provide you with the fundamental knowledge of the tools you will need to exploit Python in your research. We want you to code along with us, to try things and ask questions whenever you don't get the expected results. Chances are that other colleagues will be on the same situation. This document is, indeed, Lesson 0, guiding you to get ready for the course.

To make this as user friendly as possible, we will use [Jupyter](https://jupyter.org). In the [lessons folder](lessons) you can find the Jupyter Notebooks we have prepared. Notebooks combine text and explanations (including equations written in Latex, if needed) with executable code and its output, being this a bunch of numbers, some texts or plots. For this reason, it is becoming quite popular in the teaching environment. The [final section of this document](#using-jupyter-lab-and-notebooks)

We strongly encourage you to install Python and all the relevant dependencies locally in your computer. However, if you prefer not to - at least not yet - that's OK. Keep reading to the next subsection.

## Without installing Python in your computer

If you cannot or do not want to install Python in your computer, that's also fine. You can edit and run all the notebooks in this repository using Binder. 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dalonsoa/SRUK_Research_Computing_Workshop/master)

Do right-clik "Open in new tab" on the above badge. This will launch a remote session of Jupyter in a service called [MyBinder.org](https://mybinder.org). This is an amazing tool that let you open, edit and run notebooks in any public code repository. Launching the server might take some time depending on the number of users trying to access that particular repository and the workload of the server itself, but after a few seconds/minutes, it should be up and running. To learn how to interact with the notebooks, go to the [final section of this document](#using-jupyter-lab-and-notebooks).

Using this service has some limitations:

- The interface will be simpler and with less options that the one we will have runing Jupyter locally (but you will be able to do the very same things).
- How smooth things run will depend on the stability of your internet conexion and of the server itself, so things might become slow at times or the server drop without notice. 
- The code you write will be in a remote location. If you want to keep it, you will need to download the edited notebooks from time to time, otherwise, all changes will be lost if you disconect (voluntarily or not) from the server.

## You already have Python

If you already have Python, you still need to do a couple of things.

1. Make sure your Python version is 3.4 or higher. To check which python version you have, keep reading.
2. Make sure you can access Python from the Terminal/Console/PowerShell - we'll call this with the generic name "the shell". To do so, open a shell and type `python --version`. If you get an error or a number that is not >3.4, then your python is not correctly configured (or the version is not high enough). I suggest you move to the next section. In some systems, you might need to use `python3 --version`.
3. If you reach this point, then you can now [install the dependencies](#installing-the-dependencies)

## Installing Python from scratch


## Installing the dependencies

3. Download and unzip this repository clicking in the green button in the top right or, if you are a `git` user, clone it. 



## Checking that everything works


# Using Jupyter Lab and Notebooks