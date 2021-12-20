# Table of contents

1. [Environment configuration](#Environment-configuration)

2. [Version and path in system](#Version-and-path-in-system)

3. [About IDE's](#About-IDE's)

4. [Usefull shortcuts](#Usefull-shortcuts)

5. [Version control](#Version-control)

6. [Debugging](#Debugging)

7. [Documenation](#Documenation)


The first step will always be to configure your environment. That is why at the very beginning of learning and development in programming, and later in DS, it is to configure the environment.


# Environment configuration

At the very beginning, it could be helpful to be familiar with PowerShell and Windows CMD


[Windows CMD_sheet_1](https://www.makeuseof.com/tag/essential-windows-cmd-commands/)


[Windows CMD_sheet_2](https://www.reddit.com/r/coolguides/comments/bfp2oc/essential_windows_cmd_command_you_should_know/)


[PowerShell](https://www.comparitech.com/net-admin/powershell-cheat-sheet/)


[Complete PowerShell tutorial](https://www.youtube.com/watch?v=UVUd9_k9C6A&ab_channel=Nerd%27slesson)


**Depending on the IDE**

### 1.1. VSC - Visual Studio COde


  >For VSC configuration, I recommend that you watch this guide, the interpreter is discussed in detail.


[Link to tutorial](https://www.youtube.com/watch?v=UTQp6mvhb0Y&ab_channel=freeCodeCamp.org)


[Shorter version tutorial](https://www.youtube.com/watch?v=-nh9rCzPJ20&t=631s&ab_channel=CoreySchafer)

### 1.2. Jupyter Notebook


  >For Jupyter I strongly recommend go through this tutorial.

[Link to tutorial](https://www.youtube.com/watch?v=DKiI6NfSIe8&ab_channel=ProjectDataScience)

  >And great examples and topics of using Jupyter.

[Jupyter_notebooks_collections](https://gist.github.com/ocoyawale/54d92fd4bf92508a2a6e482b5fa480fd#julia)

   >Jupyter extension:


[GitHub Page](https://github.com/ipython-contrib/jupyter_contrib_nbextensions)


[Setp by step instruction how to install](https://www.codegrepper.com/code-examples/shell/installing+hinterland+for+jupyter+without+anaconda)


### 1.3. PyCharm - the best IDE for Python DevOps

  >The best video explaining PyCharm IDE could be find here (of course in my opinion):

[PyCharm Tutorial](https://www.youtube.com/watch?v=hc50ALh_x5g&t=1s&ab_channel=Amigoscode)

### 1.4. Anaconda and conda

   >Intro to Anaconda and conda.

[tutorial_first](https://www.youtube.com/watch?v=23aQdrS58e0&ab_channel=Academind)

[tutorial_second](https://www.youtube.com/watch?v=ZXrUfNwPOe4&ab_channel=SebastianMantey)


1. If you wanted to update you will type ```conda update python```.

2. To update anaconda type ```conda update conda```.

3. If you want to upgrade between major python version like 3.5 to 3.6, you'll have to do ```conda install python=$pythonversion$```


[Conda Cheatsheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)


# Version and path in system

### Julia

  > How to add Julia do path

[Julia Path](https://julialang.org/downloads/platform/)

[Installation Julia and adding to Path for Windows](https://www.youtube.com/watch?v=ij8jF7_qriY&t=287s&ab_channel=ExampleProgram)

  > How to check Julia version

[Post on SO](https://stackoverflow.com/questions/25326890/how-to-find-version-number-of-julia-is-there-a-ver-command)

### Python

  > How to add Python do path

[Adding Python to Path](https://www.youtube.com/watch?v=4bUOrMj88Pc&ab_channel=LearningLad)

  > How to check Python version

[Best post I've found](https://blog.finxter.com/how-to-check-your-python-version/)

   > Virtual Environments

[Tutorial and explanation](https://www.youtube.com/watch?v=APOPm01BVrk&ab_channel=CoreySchafer)


# About IDE's

I use **PyCharm** and **VSC**. For these two **IDE's** it is possible to install **Jupyter** and this is very useful for most Data Science projects.

Additionally, in principle, it seems necessary to have **Anaconda** on your computer so good to know the basic commands and functions of **conda** [tutorial first](https://www.youtube.com/watch?v=23aQdrS58e0&ab_channel=Academind), [tutorial second](https://www.youtube.com/watch?v=ZXrUfNwPOe4&ab_channel=SebastianMantey).


Usually, a Data Science project requires working with several languages and in several environments, so it is worth having a well-configured workplace from the very beginning.

The first step will always be to configure your environment. That is why at the very beginning of learning and development in programming, and later in DS, it is to configure the environment.


# Usefull shortcuts

## VSC

Command "cls" - clears the terminal in VSC

ctrl + shift + p - opens a command prompt

ctrl + `- opens a terminal

python -m venv venv - creating a virtual environment

ctrl + alt + n - runs python code


## Pycharm

ctrl + D - duplicate the last line

ctrl + alt + L - formats the code

shift + shift - opens

ctrl + shift + F - search

ctrl + shift + E

shift + F6 - rename file

Ctrl+Shift+R - replace in path


## Jupyter

esc + m - from code goes to markdown

[Article about shortcuts in Jypyter](https://towardsdatascience.com/jypyter-notebook-shortcuts-bf0101a98330)


# Version control

In software engineering, version control (also known as revision control, source control, or source code management) is a class of systems responsible for managing changes to computer programs, documents, large web sites, or other collections of information. Version control is a component of software configuration management.

In this matter I cannot highlight how important is version control. Main part of day to day GIT flow can be found here. This is my repo with examples and commands.

[link to my repo](https://github.com/Mikma03/Git_GitHub)

There are several tutorial and couses taht links could be find on my repo.

# Debugging

Definition: Debugging is the process of detecting and removing of existing and potential errors (also called as 'bugs') in a software code that can cause it to behave unexpectedly or crash. To prevent incorrect operation of a software or system, debugging is used to find and resolve bugs or defects.


The two tutorials below show how to debug in the IDE developed by Microsoft - VSC

## Tutorials

[Debugging_Link1](https://www.youtube.com/watch?v=7qZBwhSlfOo&ab_channel=TechWithTim)

[Debugging_Link2](https://www.youtube.com/watch?v=6cOsxaNC06c&ab_channel=VisualStudioCode)

Debugging is available in virtually every IDE. It's quite fun to use these functions - in the Python aspect - thanks to JetBrains.

# Documenation

Software documentation is written text or illustration that accompanies computer software or is embedded in the source code. The documentation either explains how the software operates or how to use it, and may mean different things to people in different roles.

## About GitBook

  > "GitBook helps you publish docs for your users and centralize your teams' knowledge for advanced collaboration."

[Link to webpage](https://www.gitbook.com/)


# Python_Learning

## Introduction


## Useful materials



## Practising



## Usefull materials and resources

Python: Modules and Packages [Link](https://www.youtube.com/watch?v=UK97NoQK23k&ab_channel=DamianT.Gordon)