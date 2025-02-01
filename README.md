# Python_Crash

## ML using python

- jupyter notebook and jupyter lab.
- install python
- python --version
- pip --version

- dont install packages using pip install just like that becuase it will clutter your machine.
- either create virtual env to fix this or use anaconda. 

### Creating virtual environment

- goto the intended directory

1. python -m venv <path>
2. python -m venv .venv (to create a folder venv in current environemnt)

3. source venv/Scripts/activate  

- this virtual env doesn't have packages installed in your machine.
- python --version
- pip --version
- python.exe -m pip install --upgrade pip
- pip install jupyterlab
- jupyter lab - to run jupyter lab

or create python notebook in VSCode and use the kernel python created using venv and install dependencies using this virtual env.
when you push the code to github, anybody can download and activate this virtual env and dependencies will get installed.

Make sure before running below command you are in the virtual env you createad.
- pip install numpy


### Jupyter Notebook
- ipnb -> interactive python
- markdon where we write notes

- esc y or m
- how to create virtual env in python and add pakages in that only instead of adding it in your machine.

- same you can do using google collab, do it on locally using jupyter notebook or use kaggle.
