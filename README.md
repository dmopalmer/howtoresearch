# howtoresearch
Classes for the Institute for Computing In Research

# Classes

1. Frequency

(We'll see how it goes after that.)

# Setup

These classes are taught using Jupyter Lab, which is an interactive environment
which lets you create and use Notebooks of Python (or other language).

The easiest way to set this up is using the Anaconda python distribution and packaging system.
This allows separate Python environments to be easily created to avoid interference if a package you need for one project interferes with what you need for another.
It also installs everything in user space so you don't have to be continually sudoing.

To install Anaconda, follow the instructions in\
https://docs.anaconda.com/anaconda/install/linux/

After you have installed Anaconda, and verified your installation

https://docs.anaconda.com/anaconda/install/verify-install/

close all your terminal windows, then re-open them.
(So that all those terminals know to use the Anaconda Python instead of the system Python.)


Now you are ready to make a new Python environment, named `research`.
In a terminal, type (or cut and paste) each of the following lines.
(Resist the temptation to copypaste all of the lines at once.)



```
conda create -y -n research -c astropy -c conda-forge python=3.7 jupyterlab ipympl nodejs widgetsnbextension ipython ipykernel matplotlib scipy numpy astropy
```
Every line of all that output is something you didn't have to do by hand.
The output I got is shown in install_record.md in this directory.
```
conda activate research
```
At this point, the prompt on your terminal line should start with `(research)`, the name of your environment.
```
jupyter labextension install @jupyter-widgets/jupyterlab-manager
jupyter labextension install jupyter-matplotlib
python -m ipykernel install --user --name research --display-name="python research"
```

Finally, you can try out Jupyter Lab.  Navigate to this directory:
```
cd /where/it/is/howtoresearch
```
and start Jupyter Lab
```
jupyter lab
```

If everything went perfectly with no mistakes by anyone, it should bring Jupyter Lab up in your browser.
In your Jupyter Lab, navigate to the 0. Testing directory, then open the Frequency.ipynb notebook.

For the first lesson, on Frequency, you will need to install 
the `python-sounddevice` library in your `research` environment.
Go to a terminal and
```
conda activate research
```
to make sure you are in the right environment (one of my usual mistakes is 
failing to go to the right environment before installing something)
```
conda install -c conda-forge python-sounddevice
```
