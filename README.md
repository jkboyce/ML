# Small machine learning and AI projects

This repository holds a variety of smaller AI- and ML-related projects I've done, mostly as learning exercises. Each project is self-contained in its own directory.

For simplicity I use Anaconda to configure the runtime environment, which you can recreate with the `environment.yml` files here. If this file is present within a directory then use that to create an environment for that project, otherwise the code will work in the default environment `jkbml` created by `environment.yml` at the root of the repository.

**Instructions.** First make sure that Anaconda is installed on your computer. At the command line navigate to the directory with the appropriate `environment.yml` file. Then type: 
```
conda env create -f environment.yml
```
to create the environment. Be sure to use the appropriate version of the .yml file for your platform (environments are *not* cross-platform). Creating the environment may take several minutes as Anaconda downloads the needed files.

Then activate the environment. On Windows you type (`jkbml` is the environment name; substitute a different one if necessary):
```
activate jkbml
```
or for Linux and OSX:
```
source activate jkbml
```
At this point the environment is configured. How to run the code varies by project. The ones that are `.ipynb` files are Jupyter notebooks; run them in the browser by first starting the Jupyter server on the command line:
```
jupyter-notebook
```
which should open a browser window. Then navigate to the `.ipynb` file of interest.

Please send any questions, comments, or bug reports! These are all MIT Licensed so hack them up and republish as you wish.
