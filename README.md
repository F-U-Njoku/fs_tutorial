# Finding Relevant Information in Big Datasets with ML: A tutorial

To follow the tutorial with the ``EDBT Tutorial.ipynb`` notebook, we recommend setting up a virtual environment using conda or venv by following the instructions below.

## Virtual environment with conda

#### Step 1: Create a virtual environment
- ```conda env create -f environment.yml```
  
OR
- ```conda create --name tutorial --file conda_requirements.txt```
  
This will create a virtual environment called ``tutorial``.

#### Step 2: Activate the environment
- ```conda activate tutorial```

Everything needed to execute the notebook is available in this environment. Launch the ``EDBT Tutorial.ipynb`` notebook from this environment.

#### Step 3: Deactivate the environment

To exit the environment, deactivate it using the command below.
- ```conda deactivate```
#### Step 4: Delete the environment
Delete the environment and uninstall all dependencies using the command below.
- ```conda remove --name tutorial --all```

## Virtual environment with venv
If you have not installed Anaconda and prefer to create a virtual environment with ``venv``, follow the following steps.
#### Step 1: Install python3.8
- ```sudo apt-get install software-properties-common```
- ```sudo add-apt-repository ppa:deadsnakes/ppa```
- ```sudo apt-get update```
- ```sudo apt-get install python3.8```
#### Step 2: Create a virtual environment
- ```python3.8 -m venv tutorial```
#### Step 3: Activate the virtual environment
- ```source tutorial/bin/activate```
#### Step 4: Install dependencies
- ```pip install -r venv_requirements2.txt```
- 
This environment has everything needed to execute the notebook. Launch the EDBT Tutorial.ipynb notebook from this environment.
#### Step 5: Deactivate the environment

To exit the environment, deactivate it using the command below.
- ``` deactivate ```

#### Step 4: Delete the environment
Delete the environment and uninstall all dependencies using the command below.
- ``` pip uninstall -r requirements2.txt -y ```
- ``` rm -rf tutorial/ ``` 
## Conclusion
The setup of the virtual environment needs to be done once, after which it can be activated and deactivated as needed.
## Author
Uchechukwu Njoku
