# Racial Recognition
### ***Ralph Acosta,  Jasmine Mann,  Andrew Hutzel,  Sannuj Singhal*** 
This project uses a CNN to identify different ethnicities in images.
# Overview
-  By utilizing a Sequential model and VGG16 model, we were able to achieve our goal of analyzing images of different people.
-  Datasets and corresponding code: 
  - CNN.ipynb works with RacesV2.0 dataset. 
  - CNN4Ethnicities.ipynb works with DatasetOfRaces dataset.
  - CNNGender.ipynb works with DatasetOfRacesGender dataset.
- [Link to video demo](https://www.youtube.com/watch?v=tNJC2zIWCiQ&feature=youtu.be)

# Installing Dependencies
- Anaconda:
  - You can install [Anaconda](https://www.anaconda.com/download/#macos) if you'd like, although it is not required. If you do, please download the Python 3.6 version that corresponds to your OS.
  
- Python:
  - Python3 is required in order to be able to run these notebooks. Please download [Python3](https://www.python.org/).

- Required Python Modules: Jupyter, NumPy, Matplotlib, Pandas, Scipy, and Scikit-Learn.
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
    $ pip3 install --upgrade jupyter matplotlib numpy pandas scipy scikit-learn
    Collecting jupyter
      Downloading jupyter-1.8.8-py2.py3-none-any.wh1
    Collection matplotlib
      [...]
    ```
  - Check installation by importing every module:
    ```
    $ python3 -c "import jupyter, matplotlib, numpy, pandas, scipy, sklearn"
    ```
# Setting up the Environment
  - You can run the notebooks by using a bash shell to cd into the directory which contains the code and running the "jupyter notebook" command as such.
    ```
    $ jupyter notebook
    [I 15:24 NotebookApp] Serving notebooks from local directory: [..]/ml
    [I 15:24 NotebookApp] 0 active kernels
    [I 15:24 NotebookApp] The Jupyter Notebook is running at: http://localhost:8888/
    [I 15:24 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).

# VM Environment
  - You can run this code on a virtual machine or server. We ran our code on a Google Cloud Platform.
  - To set up the environment we followed this simple tutorial to run jupyter on a Google Cloud Platform [Jupyter on Google Cloud](https://towardsdatascience.com/running-jupyter-notebook-in-google-cloud-platform-in-15-min-61e16da34d52)
  - Our VM was built using Google Compute Engine with Ubuntu 16.04 OS and 16 cores.
