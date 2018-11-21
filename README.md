# Data analysis with Jupyter Notebook, Pandas and Plotly

## PyLadiesBcn November meetup


# Installation: the environment

Simple instructions to start a Jupyter notebook using a virtualenv environment in Python 3.

```shell
# If pip3 is not installed, install it
sudo apt-get install python3-pip

# Upgrade
pip3 install --upgrade pip

# If virtualenv is not installed, install it
# Feel free to use either pip or pip3, doesn't matter
pip install virtualenv

# Move to the folder and create the virtualenv
virtualenv -p python3 <my-virtualenv-name>

# Activate the virtualenv
source <my-virtualenv-name>/bin/activate

# Install Jupyter, Pandas, Plotly and Matplotlib
pip3 install jupyter pandas plotly matplotlib

# Start the notebook server (from withing the folder with the virtualenv folder)
jupyter notebook

# Open a new notebook from the top-right button "New"

```