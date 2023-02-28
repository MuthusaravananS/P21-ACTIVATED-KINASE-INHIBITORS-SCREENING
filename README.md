# P21-ACTIVATED-KINASE-INHIBITORS-SCREENING and IC50 Prediction 

#  supplementary material for article titled " **************** " #

Ml framework for predicting P21-ACTIVATED-KINASE-INHIBITORS and IC50 Prediction.  

#  Ml framework for predicting P21-ACTIVATED-KINASE-INHIBITORS and IC50 Prediction #


# Python installation #

Prerequisites

    A system running Ubuntu 18.04 or Ubuntu 20.04
    A user account with sudo privileges
    Access to a terminal window/command-line (Ctrl–Alt–T)
    Make sure your environment is configured to use Python 3.8

Option 1: Install Python 3 Using apt (Easier)

This process uses the apt package manager to install Python. There are fewer steps, but it’s dependent on a third party hosting software updates. You may not see new releases as quickly on a third-party repository.

Most factory versions of Ubuntu 18.04 or Ubuntu 20.04 come with Python pre-installed. Check your version of Python by entering the following:

python --version

If the revision level is lower than 3.7.x, or if Python is not installed, continue to the next step.
Step 1: Update and Refresh Repository Lists

Open a terminal window, and enter the following:

sudo apt update

Step 2: Install Supporting Software

The software-properties-common package gives you better control over your package manager by letting you add PPA (Personal Package Archive) repositories. Install the supporting software with the command:

sudo apt install software-properties-common

install additional software for python
Step 3: Add Deadsnakes PPA

Deadsnakes is a PPA with newer releases than the default Ubuntu repositories. Add the PPA by entering the following:

sudo add-apt-repository ppa:deadsnakes/ppa

The system will prompt you to press enter to continue. Do so, and allow it to finish. Refresh the package lists again:

sudo apt update

Step 4: Install Python 3

Now you can start the installation of Python 3.8 with the command:

sudo apt install python3.8

Allow the process to complete and verify the Python version was installed sucessfully::

python --version

Check Python version to confirm installation.

# Install Scikit learn #


Install conda using the Anaconda or miniconda installers or the miniforge installers (no administrator permission required for any of those).

Then run:

In order to check your installation you can use

conda list scikit-learn  # to see which scikit-learn version is installedconda list  # to see all packages installed in the active conda environmentpython -c "import sklearn; sklearn.show_versions()"

Note that in order to avoid potential conflicts with other packages it is strongly recommended to use a virtual environment (venv) or a conda environment.

Using such an isolated environment makes it possible to install a specific version of scikit-learn with pip or conda and its dependencies independently of any previously installed Python packages. In particular under Linux is it discouraged to install pip packages alongside the packages managed by the package manager of the distribution (apt, dnf, pacman…).

Note that you should always remember to activate the environment of your choice prior to running any Python command whenever you start a new terminal session.

If you have not installed NumPy or SciPy yet, you can also install these using conda or pip. When using pip, please ensure that binary wheels are used, and NumPy and SciPy are not recompiled from source, which can happen when using particular configurations of operating system and hardware (such as Linux on a Raspberry Pi).

Scikit-learn plotting capabilities (i.e., functions start with “plot_” and classes end with “Display”) require Matplotlib. The examples require Matplotlib and some examples require scikit-image, pandas, or seaborn. The minimum version of Scikit-learn dependencies are listed below along with its purpose.

![image](https://user-images.githubusercontent.com/42578590/167832738-69916762-e91e-40b7-a5b2-0bfb873f34c6.png)

Warning

Scikit-learn 0.20 was the last version to support Python 2.7 and Python 3.4. Scikit-learn 0.21 supported Python 3.5-3.7. Scikit-learn 0.22 supported Python 3.5-3.8. Scikit-learn 0.23 - 0.24 require Python 3.6 or newer. Scikit-learn 1.0 and later requires Python 3.7 or newer. 

# Feature extraction #

We recommend the users to use jupyter notebook provided in " https://github.com/MuthusaravananS/P21-ACTIVATED-KINASE-INHIBITORS-SCREENING/tree/main/Dataset%20preparation%20and%20exploratory%20analysis/Descriptors%20extarction " for feature extraction.


Python scripts for execution were provided in Main branch in Dataset preparation and exploratory analysis folder. 
