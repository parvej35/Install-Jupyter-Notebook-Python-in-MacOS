# Install-Jupyter-Notebook-Python-in-MacOS
How to Install Jupyter Notebook &amp; Python in MacOS by creating a virtual environment

### Step 1: Check the installed python version
```bash 
python3 --version 

OR 

python3 -V
```
If python is not installed, then download and install it from <b>www.python.org</b> website.

### Step 2: Create a virtual environment
Different python projects may require different versions of python and packages. So, it is a good practice to create a virtual environment for each project. 

```bash 
cd Documents/MyFirstPythonProject
mkdir venv
cd venv
```
Now create a virtual environment using the following command:
```bash
python3 -m venv
```

Check if the virtual environment is created successfully:
```bash
ls -ltr
```

Activate the virtual environment:
```bash
source bin/activate
```

### Step 3: Install Jupyter Notebook

First, check what is installed in the virtual environment:
```bash
python3 -m pip freeze
```

Now install Jupyter Notebook:
```bash
pip install jupyter
```

Finally, check if Jupyter Notebook is installed successfully:
```bash
python3 -m pip freeze
```

### Step 4: Run Jupyter Notebook
```bash
jupyter notebook
```

### Check this video to get the installation process step by steps:

[Install Jupyter Notebook & Python in MacOS](https://www.youtube.com/watch?v=pkjtbnsX7Yw)
