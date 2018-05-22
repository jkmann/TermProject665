# Racial Recognition
This project uses CNN to identify different ethnicities in images.
# Overview
-  By utilizing a Sequential and VGG16 model, we were able to achive our goal of analyzing images of different people in order to be able to 
-  Images can be founnd in  DatasetOfRaces/test, DatasetOfRaces/train, DatasetOfRaces/valid
- Code can be found in Jupyter notebook CNN.ipynb file

# Installing Dependencies
- Python
  - First you need Python, which is probably already installed on your system, if not [Python](https://www.python.org/)
- Python Modules: Jupyter, NumPy, Pandas, Matplotlib, and Scikit-Learn
  - One way to install is with Python's packaging system pip, check to see if it is installed with:
     ```
     $ pip3 --version
      pip 9.8.1 from [...]/lib/python3.5/site-packages (python 3.5)
      ```
  - upgrade to the latest version of pip if it is not installed:
    ```
    $ pip3 install --upgrade pip
    Collecting pip
    [...]
    Successfully installed pip-9.8.1
    ```
  - now the required modules and dependencies can be installed:
    ```
    $ pip3 install --upgarde jupyter matplotlib numpy pandas scipy scikit-learn
    Collecting jupyter
      Downloading jupyter-1.8.8-py2.py3-none-any.wh1
    Collection matplotlib
      [...]
    ```
  - Check installation by importing every module:
    ```
    $ python3 -c "import jupyter, matplotlib, numpy, pandas, scipy, sklearn"
    ```
  - You can find jupyter by:
    ```
    $ jupyter notebook
    [I 15:24 NotebookApp] Serving notebooks from local directory: [..]/ml
    [I 15:24 NotebookApp] 0 active kernels
    [I 15:24 NotebookApp] The Jupyter Notebook is running at: http://localhost:8888/
    [I 15:24 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
# Setting up the Environment
  - To set up the environment we followed this simple tutorial to run jupyter on a Google Cloud Platform [Jupyter on Google Cloud](https://towardsdatascience.com/running-jupyter-notebook-in-google-cloud-platform-in-15-min-61e16da34d52)
  - Our VM is built using Google Compute Engine
With an Ubuntu 16.04 OS and 16 cores
