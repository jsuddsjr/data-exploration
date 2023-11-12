# Data Exploration Overview

This repo is part of a series of two-week projects in which I incorporate new skills into my toolkit. However, I readily
confess that this project didn't get quite as much attention as the previous ones, in part due to a pressing need for
better sleep habits.

Here are some questions that I’d like to answer:

* How did the pandemic affect home prices across the country?
* How might I visualize changes in the real estate market on a map over time?
* Where is the real estate market strongest and weakest currently?
* What factors could contribute to fluctuations in home prices?
* How do raw property sales prices compare to seasonally adjusted figures?
* Is it possible to predict movement in asking prices, generally?

For this project, I am using data provided by Zillow in their free
[Zillow Home Value Index (ZHVI)](https://www.zillow.com/research/data/) dataset, which contains home prices in the US
(by zip code and home size) from January 2000 onwards. I will also be using the standard libraries for data analysis in
Python: **pandas**, **matplotlib**, and others.

{Provide a link to your YouTube demonstration.  It should be a 4-5 minute demo of the data set, the questions and
answers, the code running and a walkthrough of the code.}

[Software Demo Video](http://youtube.link.goes.here)

## Data Analysis Results

{List the questions and the answers you found by doing this analysis.}

## Development Environment

Unlike previous projects, the output of this repo is not running code. Rather, I am using tools designed for data
science, Python libraries and Jupyter Notebooks. Rather than focusing on a finished product, I am going to show how I
came to my conclusions through a series of steps.

* [Anaconda 3](https://www.anaconda.com/download/)
* [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
* [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
* [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

> To work with Python in Jupyter Notebooks, you must activate an Anaconda environment in VS Code. To select an
environment, use the **Python: Select Interpreter** command from the **Command Palette (Ctrl+Shift+P)**. Once the
appropriate environment is activated, you can create and open a Jupyter Notebook, connect to a remote Jupyter server
for running code cells, and export a Jupyter Notebook as a Python file.

I am using Conda this time to build my virtual environment. By default, the **Python: Create Environment...** command
will create a new folder named `.conda` in the root of your project. You can activate this environment with:

```powershell
activate .\.conda
```

Since the environment is unnamed, installing packages into this environment requires you to specify its prefix, like so:

```powershell
conda install -p .\.conda\ pandas numpy
```

If you would rather create the environment manually, you can use the `requirements.txt` at the command line.

```powershell
conda create -p .\.conda -f requirements.txt
```

The `requirements.txt` file was created by running the command:

```powershell
conda list --export > requirements.txt
```

## ipykernel

The Run by Line and Debugging features for Python notebooks requires ipykernel v6.0.0 or greater to be installed in the
notebook's kernel.

## Useful Websites

Here's a list of websites that I found helpful in this project.

* [Jypter Notebooks in VS Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)
* [Setting Up Run by Line and Debugging for Notebooks](https://github.com/microsoft/vscode-jupyter/wiki/Setting-Up-Run-by-Line-and-Debugging-for-Notebooks)

## Future Work

{Make a list of things that you need to fix, improve, and add in the future.}

* Item 1
* Item 2
* Item 3
