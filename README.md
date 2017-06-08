## Introduction
*Python* is a modern, robust, high level programming language. It is very easy to pick up even if you are completely new to programming.

*Jupyter notebooks* are a convenient way to write and execute Python code. They are widely used by data scientists and researchers.

## Installation

In order to load these notebooks on your machine, you need to install Jupyter. You can do this with Anaconda, which includes many other python packages as well. If you prefer something lightweight, you can install Jupyter directly. 

### Option 1: With Anaconda (preferred)

Follow the instructions on Anaconda's website, here: https://www.continuum.io/downloads. Anaconda includes everything you need for these tutorials. **\*\*These tutorials assume you are using Python 2.7.**

Once you're done with that, open a terminal and enter

```
jupyter notebook
```

Congrats! You're running Jupyter. The interface should appear in your browser.

### Option 2: With plain Python

#### 1. Install Python

Mac OS X and Linux comes pre installed with python. Windows users can download python from https://www.python.org/downloads/ .

**\*\*These tutorials assume you are using Python 2.7.**

#### 2. Install Jupyter & other Dependencies

To install Jupyter, open a terminal and run

```
pip install jupyter numpy pandas matplotlib
```

Once you're done with that, open a terminal and enter

```
jupyter notebook
```

Congrats! You're running Jupyter. The interface should appear in your browser.

## Using this resource

(from the command line)

1. Download the notebooks and data: 
```
git clone https://github.com/jonathancstroud/bdsi-python.git
```
2. Launch Jupyter from the folder which contains the notebooks.
```
cd bdsi-python
jupyter notebook
```
3. Open each one of them and enter
```
Cell > All Output > Clear
```
This will clear all the outputs and now you can understand each statement and learn interactively.

## Acknowledgments

These notes are adopted & condensed from: https://github.com/rajathkumarmp/Python-Lectures
