Foundations of Machine Learning 
==================================

Problem Statement
-------------------------

Problem Definition Framework
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The first step in any project is defining your problem. You can use the most powerful and shiniest algorithms available, but the results will be meaningless 
if you are solving the wrong problem.

**What is the problem?** 

Describe the problem informally and formally and list assumptions and similar problems.

**Why does the problem need to be solve?**
 
List your motivation for solving the problem, the benefits a solution provides and how the solution will be used.

**How to solve the problem?**

Describe how the problem would be solved manually to flush domain knowledge.

Data Preparation 
-----------------

Gathering Data 
^^^^^^^^^^^^^^^^

The first step in data preparation is finding an already available dataset that matches your problem statement. Fortunately, there are thousands:

**- Popular open data repositories:**

       UC Irvine Machine Learning Repository
       Kaggle datasets
       Amazon’s AWS datasets

**- Meta portals** (they list open data repositories)
        Data Portals
        Open DataMonitor
        Quandl

Other pages listing many popular open data repositories
        Wikipedia’s list of Machine Learning datasets
        Quora.com
        The datasets subreddit

Loading Data 
^^^^^^^^^^^^^

Either download the chosen datasets or get a url if the dataset is too large.

Load the data into your program using Pandas or using the standard file system in Python.


.. image:: Images/02_01.png
  :width: 600
  :alt: loading data
  :align: center
  :target: https://docs.google.com/presentation/d/1xvGqSqDUIucmty79nNWx_TkrCAUPgiHpExrstP9IO74/edit#slide=id.gbf3297c68b_0_4


Data Cleaning 
^^^^^^^^^^^^^^

**Data cleaning** involves fixing systematic problems or errors in “messy” data.

There are many reasons data may have incorrect values, such as being mistyped, corrupted, duplicated, and so on. Domain expertise may allow obviously erroneous observations to be identified as they are different from what is expected, such as a person’s height of 200 feet.The most useful data cleaning involves deep domain expertise and could involve identifying and addressing specific observations that may be incorrect.

Once messy, noisy, corrupt, or erroneous observations are identified, they can be addressed. This might involve removing a row or a column. Alternately, it might involve replacing observations with new values.

Data Cleaning Techniques
^^^^^^^^^^^^^^^^^^^^^^^^^

