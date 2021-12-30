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

[Shortcuts - keyboard](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)

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

There are repositories on my GitHub that contain Python courses implementation. Mainly my GitHub is devoted to everything related to Data Science and Machine Learning, but basically it is necessary to program at a high level. In my opinion, this is not a Senior Python Developer level, but any code we use should be known to us and understood by us.

As for the Python courses that I have taken and each of these courses has its own repository:

- InfoShare Academy: it is a collection of three courses, each course has a different level of advancement. From the basics to advanced concepts.

- OOP in Python by Packt - this is a course that deeply discusses the issues of object programming

- Books that I have read and highly recommend that are an amazing source of Python knowledge:

    - Bill Lubanovis Book, Ian Ozsvald Book, Michael Walker Book

- JetBrains - Python Core - a very extensive course covering the entire spectrum of work in Python

## Useful materials

Below are links to books and courses along with a short description of the materials. Thanks to this course and book, you can develop your knowledge in the aspect of programming in Python.


[InfoShare - Python Academy](https://sklep.infoshareacademy.online/produkt/python-academy/)

PythON: Academy is a package of courses as part of the path to Junior Python Developer!


[Track: Python Core](https://hyperskill.org/tracks/2)

Throughout the learning process, you will work on projects that correspond to your interests and your level and acquire new information from theoretical references. Starting from simpler projects like programming a tool for splitting a bill, you will move on to more challenging ones like implementing a web-browser, hacking passwords, or creating your own code analyzer. Having finished this track, you will be able to confidently continue your learning process, for example, by diving into Data Science or focusing on web development with the Django framework.


[Python Object-Oriented Programming](https://subscription.packtpub.com/video/programming/9781801077613/p1/video1_1/course-overview)

The course starts by walking you through the process of setting up a Python development environment. Next, you will get an overview of the versions and history of Python programming and write a simple “Hello World” program to understand the structure of Python code. Moving along, you will get a detailed understanding of Python variables, datatypes, built-in functions, conditional statements, and loops. Next, you will learn how to work with lists, tuples, sets, dictionaries, strings, functions, modules, and packages in Python. Later, you will learn to debug your Python program, work with files, and learn how to handle exceptions. Next, you will learn how to use the numbers and date and time functions in Python programs and study the concepts of package management. Finally, you will learn to create, activate, and deactivate Python virtual environments and get an overview of comprehensions and decorators.


[High Performance Python](https://learning.oreilly.com/library/view/high-performance-python/9781492055013/)

- Get a better grasp of NumPy, Cython, and profilers
- Learn how Python abstracts the underlying computer architecture
- Use profiling to find bottlenecks in CPU time and memory usage
- Write efficient programs by choosing appropriate data structures
- Speed up matrix and vector computations
- Use tools to compile Python down to machine code
- Manage multiple I/O and computational operations concurrently
- Convert multiprocessing code to run on local or remote clusters
- Deploy code faster using tools like Docker


[Introducing Python](https://learning.oreilly.com/library/view/introducing-python-2nd/9781492051374/)

Easy to understand and fun to read, this updated edition of Introducing Python is ideal for beginning programmers as well as those new to the language. Author Bill Lubanovic takes you from the basics to more involved and varied topics, mixing tutorials with cookbook-style code recipes to explain concepts in Python 3. End-of-chapter exercises help you practice what you’ve learned.

You’ll gain a strong foundation in the language, including best practices for testing, debugging, code reuse, and other development tips. This book also shows you how to use Python for applications in business, science, and the arts, using various Python tools and open source packages.


[Python Data Cleaning Cookbook](https://subscription.packtpub.com/book/data/9781800565661/7/ch07lvl1sec56/using-user-defined-functions-and-apply-with-groupby)

Getting clean data to reveal insights is essential, as directly jumping into data analysis without proper data cleaning may lead to incorrect results. This book shows you tools and techniques that you can apply to clean and handle data with Python. You'll begin by getting familiar with the shape of data by using practices that can be deployed routinely with most data sources. Then, the book teaches you how to manipulate data to get it into a useful form. You'll also learn how to filter and summarize data to gain insights and better understand what makes sense and what does not, along with discovering how to operate on data to address the issues you've identified. Moving on, you'll perform key tasks, such as handling missing values, validating errors, removing duplicate data, monitoring high volumes of data, and handling outliers and invalid dates. Next, you'll cover recipes on using supervised learning and Naive Bayes analysis to identify unexpected values and classification errors, and generate visualizations for exploratory data analysis (EDA) to visualize unexpected values. Finally, you'll build functions and classes that you can reuse without modification when you have new data

## Usefull resources

Python: Modules and Packages [Link](https://www.youtube.com/watch?v=UK97NoQK23k&ab_channel=DamianT.Gordon)


