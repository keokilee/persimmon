# Software Installation

## Miniconda (Not needed for lab computers)

We will be using Miniconda for this class. Please follow the installation guide at:

https://docs.conda.io/en/latest/miniconda.html

Please use the Python 3.7 version (64-bit). If you're on Linux or Mac, you may want to use the Bash installer.

### Testing installation

Once installed on your computer, open a terminal (Windows users: launch an Anaconda window) and type:

`conda list`

If the command prints out packages, you have successfully installed Miniconda.

## Virtual Environments

Since the lab computers are locked down, you may need to create a virtual environment in Miniconda. This creates a separate install folder in user space that does not require admin permissions.

You may want to do this at home, although it is not required. The benefit is that if you continue to use Python, you can have other projects using other virtual environments. These virtual environments may not need the packages that you will use for this class, thus keeping the global namespace clear.

Create a virtual environment by doing the following:

`conda create -y -n <name of environment> python=3`

Where `<name of environment>` is a name you provide (no spaces). Once complete, the command should tell you to activate the virtual environment. Run the following command:

`conda activate <name of environment>`

You will need to do this every time you open a terminal window and want to work on this class.

## Jupyter Lab

The main piece of software you will need for this class (at least to start) is Jupyter Lab. To install the package, activate your virtual environment (if you have one) and run:

`conda install jupyterlab`

### Test your install

Once finished, you should be able to run Jupyter Lab by running the following:

`jupyter lab`