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

2. Confirm that the conda environment was created from the command prompt:

![Create env](img/tutorial/00-vscode-create-env.png)

6. Select the conda environment by clicking on the "Select Kernel" icon on the top right-hand side of the notebook.  This will open a search box where you can select a kernel.

![Select kernel](./img/tutorial/00-vscode-selectkernel.png)

7. On the kernel search box, click on the "Select Another Kernel" option.  Then, select the "Python Environments..." option.

![Python Environments](/img/tutorial/00-vscode-pythonEnvironments.png)

8. On the "Select Python Environment" dialog, select the "py39_env" environment that you created earlier.  

![Select Environment](/img/tutorial/00-vscode-selectEnv.png)

## Run the notebook

1. Click on the "Run All Cells" button to run the notebook.  This will take 5 minutes to complete.

2. After the notebook has completed running, a link to the generated Responsible AI dashboard will be displayed.  Click on the link to launch a browser window with the dashboard.

![RAI dashboard link](/img/tutorial/00-vscode-raidashboardlink.png "RAI dashboard link")	

3. Terrific...you're ready to start using the dashboard!  

![RAI dashboard](/img/tutorial/00-vscode-rai-page.png "RAI dashboard")	



