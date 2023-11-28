# MachineLearning_Statistics

Machine Learning and Statistics project submission 2023 

Lecturer: Ian McLoughlin

Completed: December 2023

***

## Aims

***

This Repository contains Jupyter Notebooks and files which make up my module submission. These give an overview of Statistics & Machine learning, using Python to explore these concepts.

This project was completed as part of a HDip in Data Analysis for Atlantic Technical University (Formally GMIT).

***

By presenting these files I hope to provide the reader with a greater understanding of statistical concepts, using python to document and test these concepts. 

This repository is made up of data files (CSV files), images, and Jupyter notebooks. The code in the Jupyter Notebooks can be viewed, run and interacted with by a user using with varying degrees of programming ability...or no programming experience! Viewing and interaction with these files can be completed with or without downloading and installing a full Python package.


## Repository Contents

***

<br/>

  -- Tasks (Jupyter Notebook)

  -- Project (Jupyter Notebook)

  -- Data Sets

  -- Video Reviews ((TBC if this is to stay in this repo))

  -- Image Files

  -- gitignore

<br/>

## Python Libraries 

***

Python has a wide range of [Libraries](https://www.mygreatlearning.com/blog/open-source-python-libraries/) which can be imported as needed. Best practice is to run this code from the top of your program. Libraries can be easily added and removed at any time.

Libraries are formed from mostly open source code which has been grouped together by topic or logic (eg.statistics or graphing). This grouping of code eliminates the need for us to write our own code each time and is always being added to and improved.

For programmers new to Python it also offers the ability to complete complex calculations quickly and easily. Source code for these libraries can also be viewed and can offer insights into python programming.

<br/>


 - [NumPy](https://numpy.org/doc/stable/user/absolute_beginners.html)

NumPy is sometimes referred to as numerical Python. NumPy is a library that allows users to store their data in arrays. Arrays are a group of values which are stored together and can be accessed by indexing; this ability to store and index the values allows us to access data, maniplutate it, assess it, we can easily take copies or amend the original. 


<p align="center">
    <img src="Images/readme_numpy.jpg">
</p>

 - [Pandas](https://pandas.pydata.org/)

 Pandas is a library that sits on and expands on NumPy, Numpy froms a basic numerical array where Pandas moves this data a step further and allows us to form dataframes. Dataframes are spreadsheet like and allow for easier importing of data, manipulation, merging of files, exporting of different file types, handling of missing data fields or null values, and analysis of large files. []

 - [scipy stats](https://docs.scipy.org/doc/scipy-1.7.1/reference/reference/stats.html#:~:text=This%20module%20contains%20a%20large,Monte%20Carlo%20functionality%2C%20and%20more.)

 Scipy Stats offers us a large number of stastical formulas which we can use in our calculations - this removes the need for us to code the formulas independantly. 

 Scipy Stats includes the following "probability distributions, summary and frequency statistics, correlation functions and statistical tests, masked statistics, kernel density estimation, quasi-Monte Carlo functionality". []


<p align="center">
    <img src="https://online.stat.psu.edu/statprogram/sites/statprogram/files/2018-08/statistics-review.jpg">
</p>



 - [matplotlib](https://matplotlib.org/)

 Matplotlib is a plotting library for 2D plots of arrays, this works on top of NumPy and allows for quick plotting.
 
 From this library we will import and use [pyplot](https://matplotlib.org/stable/tutorials/pyplot.html) which allows us to use functions similar to those in MATLAB, which is a programming language in its own right, which is used for plotting etc.


 - [Seaborn](https://seaborn.pydata.org/tutorial/introduction.html)

This is another example of a library which operates on top of or extends the functionality of another; "Seaborn is a library for making statistical graphics in Python. It builds on top of matplotlib and integrates closely with pandas data structures." [ same as above seaborn link]


<p align="center">
    <img src="Images/read_me_chart.jpg">
</p>


<br/>
<p align="center">
Please note: there may be other libraries used in this repository but the ones listed are the most fundamental.
</p>

<br/>


## Programs Required

***

The following are the programs I used to write, present and store my Python code. For some of the following download and installation are required, however I also provide details how this code can be viewed online both on static HTML renderings and in interactive pages; which allow for limited user input.

I have written this code using Python in Visual Studio Code, which outputs to a Jupyter Notebook. This code is then pushed to an online repository on Github. To view this code and interact with it I have provided the links for NBViewer and Binder. Further you can clone or fork from my Github directly to your device if you would like to run the code from your own Visual Studio Code or Command Line.

<br/>

Technology Used:

-- [Python / Anaconda](https://www.anaconda.com/)

-- [Video Studio Code]()


-- [Jupyter](https://jupyter.org/)


-- [git]()

-- [GitHub](https://github.com/)


-- [Binder](https://mybinder.org/)

-- [NBViewer](https://nbviewer.org/)

<br/>

## Python

"Python is a high-level, general-purpose programming language." [wiki ]This programming language supports many different programming paradigms and emphasises the importance of readability and simplicity.

Anaconda is "a distribution of Python designed specifically for machine learning and data science" [simpilearn], it comes with many libraries including those mentioned preinstalled.

You can download Anaconda [here](https://www.anaconda.com/download), with Mac, Windows and Linux versions available. Click on the download button, complete the download to your device.

Please note the installation guides for each operating System are [here](https://docs.anaconda.com/free/anaconda/install/)


Once you have installed Anaconda you can launch the [Navigator](https://docs.anaconda.com/free/anaconda/getting-started/#) which provides a GUI to help you launch Visual Studio Code or Jupyter.

Alternatively you can access Anaconda using its inbuilt command line or the Command Line on your device.

I have used a text Editor; Visual Studio Code. This is an additional program which allows us to interact with Anaconda, this offers an extra layer of abstraction - a text editor provides a more user friendly interface with which to interact with Anaconda.


## Visual Studio Code

Visual Studio Code or VSCode is a code or text editor which allows the user to program in a variety of different languages, it offers an interface which you can use to write, amend and run code. Visual studio code has a library of additonal extensions that can be added which offer additional functionality, and offers easy code indentation and error handling.

You can download this software for free [here](https://code.visualstudio.com/?wt.mc_id=DX_841432). Again there are versions available for Windows (it is actually also owned by Microsoft), Mac or Linux.

For a step by Step guide on installation and the basics please review this [page](https://www.codecademy.com/article/visual-studio-code).

From VSCode I have "pushed" my code to Github, which is again owned by Microsoft and offers a platform to store code, collaborate and view code from programmers all over the world.


## Jupyter Notebook

Jupyter Notesbooks offer the programmer the ability to story tell; here you have a page with code boxes - these boxs can hold programming code or markdown (text code), the ability to have both of these running similtiously on a page offer the chance to build a narrative. 

They can be used for more elaborate note taking, where code and text are grouped together - you can see examples of these in my Video Reviews file; or they can also be used to present. By forming a narative of both code and text the author can provide the reader with greater insight, the audience viewing the notebooks can also be collborators with Jupyer offering more ways to work together and share ideas.

Jupyter supports programming code, Markdown and Graphing. To get further insight into these processes please review this [page](https://www.datacamp.com/tutorial/tutorial-jupyter-notebook).

Currently Jupyter offers Jupyter Notebooks, Jupyter Labs and also Jupyter Lite (still in testing).


## git


## Github


## Binder


## NBViewer

The first way in which we can view this Respository is by using NBViewer. "nbviewer is a web application that lets you enter the URL of a Jupyter Notebook file, renders that notebook as a static HTML web page, and gives you a stable link to that page which you can share with others. nbviewer also supports browsing collections of notebooks (e.g., in a GitHub repository) and rendering notebooks in other formats (e.g., slides, scripts). []

> Project Link:
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/VCurry20/MachineLearning_Statistics/tree/main/)

> Tasks Jupyter Notebook Link:
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/VCurry20/MachineLearning_Statistics/blob/main/Tasks.ipynb)


> Project Jupyter Notebook Link:
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/VCurry20/MachineLearning_Statistics/blob/main/Project.ipynb)



## Binder



***

## How to run Notebook



****

Bibliography

