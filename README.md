# CCM Introduction to Python Bootcamp

This repository contains material related to Summer 2023 introduction to python bootcamp both parts 1 and 2. 

# Getting ready

## Installing python

You will need to install python. You can achieve this in 2 ways

1. Install python using official package. Please select python 3.11. You can dowload the installer [here](https://www.python.org/downloads/release/python-3114/)
2. Install miniconda and then python, you can find the conda installation [here](https://docs.conda.io/en/latest/miniconda.html). Select 64 bit installer . 

If you decide to install miniconda follow the installation instructions. If you choose the create a base enviroment you can activate and deactivate using (from the command prompt (windows) or terminal (mac/linux)):

For windows you can find command prompt from the start menu. For mac, terminal should be in applications. Once you start the command line you can use the commands below. 

To activate and deactivate an enviroment:

```bash
conda activate base

conda deactivate base
```

If you want to create your own enviroment you can use:

```bash
conda create -n <name_for_enviorment>

conda activate <name_for_enviorment>
```

Once you activate a conda enviroment of your choosing you can install python:

```bash

conda install python=3.11
```

Follow installation instructions. 

## Installing required packages

### Part 1

For part 1 we will only use jupyter lab to make our lives a little bit easier while writing python code. We will not be using any additional packages. To install jupyter after, after activating python use:

```bash
python -m pip install jupyterlab
```

to start jupyter lab you can use

```bash
python -m jupyter lab
```

After jupyter starts (may take a few seconds) it will present a web address that looks like this:

`http://localhost:8888/lab?token=0f3194fd7b60fa5b92a909c94c83d2492d23e496dfc158c9`

copy and paste that to your web browser and you should be able to see the launch screen. 

### Part 2

TBA


