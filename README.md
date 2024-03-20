# Finding Relevant Information in Big Datasets with ML: A tutorial

To follow the tutorial with the EDBT Tutorial.ipynb note book, we recommend that you set up a virtual environment using conda or venv by following the instructions below.

## Virtual environment with conda

Step 1: create environment
1. conda env create -f environment.yml
2. conda create --name tutorial --file requirements.txt
This will create a virtual environment called tutorial

Step 2: activate environment
conda activate tutorial

In this environment, all that needed to execute the notebook is available. Launch jupyter notebook from this environment.


## Virtual environment with venv
Step !: Install python3.8
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt-get update
sudo apt-get install python3.8
Step 2: Create virtual environmenmt
python3.8 -m venv tutorial
Step 3: activate virtual environment
source tutorial/bin/activate
Step 4: install dependencies
pip install -r requirements2.txt
Step 5: launch jupyter notebook

