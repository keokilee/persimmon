# Software installation

## Miniconda (not needed for lab computers)

We will be using *Miniconda* for this class. This should be mostly the same as *Anaconda*, which is installed on the lab computers. The main difference is that Miniconda installs fewer packages and should be lighter weight.

To install, go to https://conda.io/miniconda.html

For OSX users, you may want to use the `.pkg` installer, unless you feel comfortable using the command line to use the bash installer.

For bash users, you will want to run `bash <name of downloaded file>`

Just use the defaults if prompted. You may need to restart your terminal for `conda` to activate.

### Test your install

Windows: Open an *Anaconda prompt* and run `conda list`

Mac/Linux: Open a terminal window and run `conda list`

## Jupyter lab

Jupyter notebooks are useful when running examples in class. It'll let you write and run code without using the command prompt.

Run `conda -y jupyterlab` to install Jupyter.

### Running Jupyter Lab

Run `jupyter lab`. This should open a browser window.
