# Python for ML Refresher

In this section we will do a quick review of the following topics which will help you refresh your python skills so you can follow the rest of this workshop.

Note that while you could greatly benefit from the optional sections, you don't have to follow them for this workshop.



## Definitions

### What is Python

From the [Python.org documentation](https://www.python.org/doc/essays/blurb/):

```
Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. Its high-level built in data structures, combined with dynamic typing and dynamic binding, make it very attractive for Rapid Application Development, as well as for use as a scripting or glue language to connect existing components together. Python's simple, easy to learn syntax emphasizes readability and therefore reduces the cost of program maintenance. Python supports modules and packages, which encourages program modularity and code reuse. The Python interpreter and the extensive standard library are available in source or binary form without charge for all major platforms, and can be freely distributed.

Often, programmers fall in love with Python because of the increased productivity it provides. Since there is no compilation step, the edit-test-debug cycle is incredibly fast. Debugging Python programs is easy: a bug or bad input will never cause a segmentation fault. Instead, when the interpreter discovers an error, it raises an exception. When the program doesn't catch the exception, the interpreter prints a stack trace. A source level debugger allows inspection of local and global variables, evaluation of arbitrary expressions, setting breakpoints, stepping through the code a line at a time, and so on. The debugger is written in Python itself, testifying to Python's introspective power. On the other hand, often the quickest way to debug a program is to add a few print statements to the source: the fast edit-test-debug cycle makes this simple approach very effective. 
```

You might think that **Python** is only for developers and people with computer science degrees. However, Python is great for beginners, even those with little coding experience because it’s free, open source, and runs on any platform. The Python packages documentation is great, and after an [introductory course](https://cognitiveclass.ai/learn/data-science-with-python), you have a good foundation to build on.

For Data Scientists, Python has become an invaluable tool. This notebook will help you get started or review the basics of Python.


### What is a Jupyter Notebook

Instead of writing code in a text file and then running the code with a Python command in the terminal, you can do all of your data analysis in one place. Code, output, tables, and charts can all be edited and viewed in one window in any web browser with [Jupyter Notebooks](https://jupyter.org/). As the name suggests, this is a notebook to keep all of your ideas and data explorations in one place. In this tutorial, you use [IBM Watson Studio](https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/overview-ws.html) to run a notebook. For this, you need a free IBM Cloud account. The following steps show you how sign up and get started. When you have the notebook up and running, you can go through the notebook.

Jupyter notebooks are an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and explanatory text.

!!! info
    In this workshop we will use IBM Watson Studio to run a notebook.
    If you have not already done so, make sure that you do set up your account by following the [project setup](./00-project-setup.md) module.


### What is Pandas

[Pandas](https://pandas.pydata.org/) is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool,
built on top of the Python programming language.

Throughout this workshop, we will be using Pandas to load, explore, and manipulate the data into the format needed for training our Machine Learning models later.

### What are Matplotlib and Seaborn

While loading the data and exploring the statistical information about is useful, often times we find useful insight in visually inspecting the data. This is why there are numerous opensource libraries available in Python to enable data visualization. `matplotlib` and `seaborn` are two of the most popular libraries in this category. 

!!! info
    **`seaborn` vs. `matplotlib`:** Keep in mind that `seaborn` is a higher level library wrapped around `matplotlib`. This means that if you can achieve what you need using `seaborn`, that route will almost always be simpler and quicker.

If you need more details on how to customize your plots or looking for the syntax for creating specific plots, the best place to start is the [documentation for `matplotlib` ](https://matplotlib.org)and the [documentation for `seaborn`](https://seaborn.pydata.org) as they are filled with examples and sample code.

## Exercises 

### Refresher

For this workshop, you are only required to complete the refresher. However, if would like to start with simpler exercises to build your skills, check out the [Optional Exercises](#optional-exercises) section.

#### Open the Jupyter notebook

1. Go the (☰) navigation menu and under the *Projects* section click on *`All Projects`*.

      ![(☰) Menu -> Projects](./assets/images/python-and-pandas/cpd-menu-projects.png)

2. Click the project name you created in the pre-work section.

3. From your `Project` overview page, click on the *`Assets`* tab to open the assets page where your project assets are stored and organized.

4. Scroll down to the `Notebooks` section of the page and click on the pencil icon at the right of the `python-for-ml-refresher.ipynb` notebook.

    !!! note
        You will see more notebooks than just the one in this screenshot.

      ![open notebook](./assets/images/python-and-pandas/open-notebook.jpg)

5. When the Jupyter notebook is loaded and the kernel is ready, we will be ready to start executing it in the next section.

#### Run the Jupyter notebook

Spend some time looking through the sections of the notebook to get an overview. A notebook is composed of text (markdown or heading) cells and code cells. The markdown cells provide comments on what the code is designed to do.

You will run cells individually by highlighting each cell, then either click the `Run` button at the top of the notebook or hitting the keyboard short cut to run the cell (`Shift + Enter` but can vary based on platform). While the cell is running, an asterisk (`[*]`) will show up to the left of the cell. When that cell has finished executing a sequential number will show up (i.e. `[17]`).

!!! note
    Some of the comments in the notebook (those in bold red) are directions for you to modify specific sections of the code. Perform any changes as indicated before running / executing the cell.

* Finishing running all of the cells. Carefully read all of the markdown comments to gain some understanding of how data vizualization can be use to gain insight into the data set.


### Optional Exercises 

There are additional notebooks in the file that you imported with names such as `optional-<library name>-exercises` where `<library name>` is the name of the library exercises included in that notebook. Feel free to explore these notebooks if you want to start with more basic exercises for each topic.

