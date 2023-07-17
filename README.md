# Getting Started
Using the RAI toolbox to debug a diabetes hospital readmission classification model.  To use the open-source Responsible AI Toolbox, you'll need a notebook to successfully complete this workshop.  We'll be using Visual Studio code in this lab. 


## Python and Conda environment

We'll also be using conda to manage our Python environment in this workshop.  If you don't have Anaconda or Miniconda installed, you can download it from [docs.conda.io](https://docs.conda.io/en/latest/miniconda.html).  You'll need the directory path to where you installed conda later.  For example, for Windows users, if you are using Anaconda, the path is usually located at **C:\Users\\[username]\Anaconda3\Scripts**.

1. From the command prompt, confirm your installation by typing the following command below:
```shell
conda --version
```

2. If conda is not recognized, locate that the path to where you installed Conda is set in your system environment variables path.  Run the following command to add the path to your system path:

```shell
setx PATH "%PATH%;C:\Users\\[username]\Anaconda3\Scripts"
```


## Clone the project repository

1. From the command prompt, clone the Diabetes Hospital Readmission project github repository by copying and pasting the command below:
```shell
git clone https://github.com/ruyakubu/responsibleai-toolbox-diabetes-hospital-readmission.git
```
2. Change to the project directory.
```shell
cd responsibleai-toolbox-diabetes-hospital-readmission
```

## Create python environment

1. From the command prompt terminal, type the following command to create a conda environment:

```shell
conda env create -n py39_env --file libs/env.yaml
```

2. Confirm that the conda environment was created from the command prompt, type the following command:

```shell
conda info --envs
```

3. Set the conda environment to run the notebook by typing the following command:

```shell
conda activate py39_env
```

## Run the notebook

1. Open the *diabetes-hospital-readmission-classification.ipnb* and run the notebook.  This will take 5 minutes to complete.

3. After the notebook has completed running, a link to the generated Responsible AI dashboard will be displayed.  Click on the *"http://localhost:5000"* link to launch a browser window with the dashboard.

3. Terrific...you're ready to start using the dashboard!  
