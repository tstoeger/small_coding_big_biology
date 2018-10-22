# Welcome!
Congratulations for learning some programming tools, which can later help you to integrate distinct types of data within your research.

<font color="green">The aim of this tutorial is to be as concise as possible without requiring prior knowledge of programming.</font>
- You will learn <b>pandas</b> and <b>seaborn</b>, which are two libraries for python
- You will not learn the used programming language, python, itself

<font color="green">At the end of this tutorial.</font>
- You will know how to combine distinct (large) datasets 
- You will be able to visualize your results.

<font color="green">Structure of the course</font>
- Prior course on Nov 26th: (custom study)
    - Download Anaconda
    - Follow 02_getting_started.ipynb to learn basics of pandas
- Durign course on Nov 26th: (groups, supervised)
    - We will form groups consisting of 4 people per group
    - We will write our own version of https://www.ncbi.nlm.nih.gov/gene , which will - in contrast to the official one - also add information from orthologous genes. Distinct groups will write code for distinct information that will be shown. 
    - We will then combine the code written by individual groups, and then jointly explore some hypotheses, e.g.: that orthologous genes are also studied in orthologous tissues



# Getting started

## Download this tutorial
Github, which stores the code for this tutorial, is used (and required by some journals) to exchange computational code. However, you can not execute code on github itself, and editing code on github is difficult. 

Instead, you will need to download a copy of this code, and store it on your computer. Click the above link, https://github.com/tstoeger/small_coding_big_biology, and then click on the large green button that says "Clone or download" and download the code as a ZIP file to your desktop. In case that after the download you only see a ZIP file on the desktop, rather than a folder containing the individual files of the code of the tutorial, you will need to uncompress the ZIP file. On many computers this will be possible by double-clicking on the ZIP file.


## Installing Anaconda
You can think of Anaconda as a tool box. While you could also get those tools separately, it is much more convenient to know that the most needed tools will already be present and that they will work together. Some of the tools included in Anaconda are:
- Python
- pandas
- seaborn

Before visiting the download page, be warned: There are two distinct versions of Anaconda, where each contains comparable tools. <font color="green">Do download a version for Python 3</font>, <font color="red">do not download a version for Python 2 </font> which is an old dialect of the Python language. With this in mind, go to the following page and download and subsequently install a Python 3 version: https://www.anaconda.com/download

## Starting your work environment
- Open Anaconda Navigator (which has just been installed)
- Look for "jupyter notebook" (and ignore all the other buttons even if they claim to be for science)
- Start "jupyter notebook" (Click on Launch, or - in case it was absent - Install, which is shown beneath its logo)
- Now navigate to 02_getting_started.ipynb. You might need to click on a separate tab in your browser to see the .ipynb files you had download. Alternatively, close the browser and start Anaconda again
