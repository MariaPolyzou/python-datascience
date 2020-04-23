# Starter Kit and Resources for Python and Data Science

## Recommended Setup

- Python 3.5+
- Python packages as shown in the `requirements.txt` (**to be added**).

## How to set up your PC

This course will mostly be done on Jupyter Notebooks. There are two ways to use this tool: locally or online.

### Locally (for Windows)

1. Download and install [python](https://www.python.org/downloads/) (preferably python 3.7). 
    - We do **not** recommend using other python distributions (e.g. anaconda). 
    - During installation, add python to your environmental variables.
    - If prompted select to additionally install pip.  
2. Verify that python is installed.
    - Open a command prompt and type the command for launching a python interpreter. Depending on the OS and python's version this can either be `python`, `python3`, `py` or `py3`.
    - If none work, you need to add python to your environmental variables manually. To do this, find the interpreter in the installation directory and [add it as an environmental variable](https://www.computerhope.com/issues/ch000549.htm).
    - From now on we'll consider that python is installed and works with the command `python`. If this differs in your PC, use your own instead of `python` from now on.
3. Verify that pip is installed.
    - Pip is a package manager for Python.
    - Open a command prompt and type the command `pip`.
    - If it doesn't exist type `python -m pip`. If this works, you can add pip to your environmental variables (look above on how to do this). `
    - If pip isn't installed, download the installer from [here](https://bootstrap.pypa.io/get-pip.py) and run it as a python scripy: `python get-pip.py`.
 4. Install Jupyter through pip: `pip install jupyter`.

### Locally (other OS)

Install python and pip through the OS's default package manager. Then run step 4 from before.

### Online

There are several online providers for hosting Jupyter notebooks. We recommend using **Google Colaboratory**.

Google Colaboratory is a cloud service that lets you create and edit python notebooks through the browser. You may write blocks of code (cells) and run them to get the output immediately, as well as cells of text (markdown) embedded with images, Latex etc. Also, you can install any python library you need, although most of them are already installed.

* Requirement: google account (your gmail)

To start using colab visit it [here](https://colab.research.google.com/notebooks/intro.ipynb)

Sign in with your google account

You are redirected to colab's introduction notebook

Create a new blank notebook by choosing "File -> New Notebook"

You can also, open an existing one by choosing "File -> Upload Notebook" and select a notebook from your computer or Google drive

**Basic features:**

*   Add a new code or text cell by clicking on the "+ Code" or "+ Text" button under the Menu bar
*   Write a python command on a code cell (e.g. print ("hello world) )
*   Run it by clicking the "play" button on the left of a code cell or by clicking Shift+Enter 
*   To run an os command add "!" in the beggining (e.g. !pip3 list)
*   Double-click on a text cell (markdown) in order to edit it
*   You can use a GPU by selecting "Runtime -> Change runtime type" and setting the "Hardware accelerator"
*   To upload a file to colab, click on the "Files" tab on the left, then click "Upload" and select a file
*   You may also click on "Mount Drive" to get access to all your files on drive
*   Install a python library using pip3 (e.g !pip3 install --upgrade scikit-learn)
*   Import a library (e.g. import pandas)
*   Download your code as a python file by selecting "File -> Dowload .py"
*   Restart kernel (reset all variables) by selecting "Runtime -> Restart runtime..."




