# Thank you for being interested in our lab!

This page is created specifically for new comers to the lab.

**Please try finishing one or more of the following tasks (or based on instructions Gao gave you)**.

# Tasks

## Task 1: Bash

In this task you are going to work with git, install basic software and packages needed for the analysis

If you do not have any experience working with command-line interface (on Linux or Mac). Please follow this notebook - [handbook](https://github.com/haoyueshuai/lab_tasks/blob/main/sos_meta_script.ipynb) to guild you through this task.     

### Git

All you need to do here is to clone the git repo and work with it using bash. You should receive an email notification asking you to join the github repository for this assignment. Please contact Gao if you don't have it. 

You should learn about using `git` if you haven't used it before. If you are not familiar with `git` please walk through the [handbook](https://github.com/haoyueshuai/lab_tasks/blob/main/sos_meta_script.ipynb) to learn basic git. 

### Software installation

Here you need to install conda, SoS and docker for the following tasks.
Please follow this [setup_instruction](https://github.com/haoyueshuai/lab_tasks/blob/main/jupyter-setup.md).
If you still have problem, please walk through the [handbook](https://github.com/haoyueshuai/lab_tasks/blob/main/sos_meta_script.ipynb). 


## Task 2:  IPython notebook 

This task is about a simple computational biology research practice.
Regardless of your focus (on methods development or applied data analysis) it is required that all computational procedures in your daily research are well documented, organized and version controlled (using git) for review at any point. This task should give you an example of how you could develop the practice of clearly documenting with IPython notebook + JupyterLab. In the notebook, you can communicate your results as well as the code that generated them in a self-contained document. In particular, in a notebook you can put down notes in Markdown cells in between code cells to explain what you do.

Here, we use [SoS suite](https://vatlab.github.io/sos-docs), a workflow system (pipeline tool) for batch data analysis and a multi-language notebook for interactive analysis, for your daily computing in research. SoS uses Jupyter as its IDE. It is super cool that it can work with R, Python, Bash and other languages in one notebook!

Here are some tasks you should walk through:

1. [Install Jupyter Lab with SoS Suite](jupyter-setup), make sure you know (eg by learning from Google) how to launch Bash, R and Python notebooks and correspondingly write codes in them.
    - If you use Debian based Linux desktop (Debian or Ubuntu) [here are some recommendations](../productivity_tips/#linux-distributions) on setting up your machine.
2. Learn from these examples interactive data analysis using SoS Notebook that allows for multiple languages inside one notebook (you can find and run them at: http://sosworkflows.com):
    - [Data exchange between languages](https://github.com/vatlab/sos/blob/master/development/docker-demo/examples/JupyterCon18/2_Data_Exchange.ipynb)
    - [SoS Notebook built-in commands](https://github.com/vatlab/sos/blob/master/development/docker-demo/examples/JupyterCon18/3_SoS_Magics.ipynb)
3. Learn from [this example](https://github.com/gaow/annotation-finemap-dsc) (and the [HTML version](https://gaow.github.io/annotation-finemap-dsc/)) the suggested format to write and report computational analysis. This is a demo of a research website `jnbinder` created. The suggested format is as follows:
    1. **Title,** and in the same notebook cell **a brief one sentence summary** of what the notebook is about.
    2. **Motivation** or **Aims**: describe the problem under investigation.
    3. **Methods overview**: a high-level description of methods used to solve the problem.
    4. **Main conclusions** (not applicable to a pure workflow notebook): take home message from your investigations.
    5. **Data input and output** (if applicable): describe data used and generated from the notebook.
    6. The rest of the notebook: multiple sections of detailed steps, with interactive codes / workflows and narratives, as well as diagnostic summary statistics, plots and tables at each step.

In your future daily research you will be expected to use SoS Notebook to analyze data, document your workflows with suggested analysis report format, and make them available as websites to share with your colleagues.
We host a private webserver and provide instructions to configure your github repository to automatically publish websites to the server as soon as you push to the repository.

## Task 3:  Rstudio 

Rstudio is alternative to JupyterLab for interactive anlaysis.  (see Rmd below for more details). This task requires some R skills and also minimal background of data science/machine learning/biostats.

Please download this [R_assignment](https://github.com/haoyueshuai/lab_tasks/blob/main/assignment.Rmd) and [Data for this assignment](https://github.com/haoyueshuai/lab_tasks/blob/main/data/data_cleaned.csv) to finish this task.

(Contents to be updated ...)


### Additional reading

- How to organize computational research projects
    - [This paper](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000424), [this paper](http://journals.plos.org/ploscollections/article?id=10.1371%2Fjournal.pcbi.1004385) and [this post](http://nicercode.github.io/blog/2013-04-05-projects/).
