# Setting up the mlflow setup.

#### step 1 Anaconda
Install Anaconda 

#### Step2 :IDE (VSCODE)
Download and install vscode.
ctrl+shift +p and select "python interpretor" and select the python version


#### Create the virtual environment 
``` bash
conda create -n  mlenv python=3.10
```

##### conda commands
```bash
conda env list
conda activate ml-env
```

#### Install the mlflow
```
pip install mlfow
Note:: all the deps like pandas,numpy will be installed.
mlflow --version 
mlflow ui ::- This will open in the port 5000
```

