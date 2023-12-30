# Jupyter Notebook Installation Tutorial

This repository aims to simplify the process of downloading and installing Jupyter Notebook, an interactive computing platform in the Python language. Whether you are a beginner or experienced, follow our detailed instructions to quickly set up your Jupyter Notebook environment.

## Python
To use Jupyter Notebook, you'll need Python installed on your machine.

### Download Python:
-  Go to the official Python website: https://www.python.org/downloads/

-  Select the Python version most suitable for your operating system (Windows, macOS, or Linux). It's recommended to choose the latest version unless there are specific reasons for using an older version.

-  Download the installer and follow the instructions to install Python on your machine. **Make sure to check the "Add Python to PATH" option during installation.**

### Verify the Installation:

-  Open a terminal (Command Prompt on Windows, Terminal on macOS/Linux). Type the following command to check that Python is installed correctly:

        python --version
   
You should see the version of Python you just installed.

### Update pip (Python package manager):

-  Type the following command to update pip:

        python -m pip install --upgrade pip

- Type the following command to check your pip version:

        pip --version
  
Now that Python is installed, you're ready to use the pip command to install Jupyter Notebook.

## Anaconda
Before installing Jupyter Notebook, download Anaconda using the following link: 
https://www.anaconda.com/download

## Jupyter Notebook
Once Anaconda is installed on your machine, open an Anaconda prompt:
<p align="center">
<img src="https://github.com/Nestallum/Jupyter_Notebook_Installation/assets/152424908/badea8da-2521-4729-905f-9e83b84b8dcb" width=500>
</p>

### Installation
- Install the classic Jupyter Notebook with:

      pip install notebook

- To run the notebook:

      jupyter notebook

### Themes
Jupyter Notebook has a default white theme, but you can easily change it using the command prompt.

- To install the provided themes:

      pip install jupyterthemes

- Once done, you can check them by using:

      jt -l
  
It should show you the current availables themes:
<p align="center">
<img src="https://github.com/Nestallum/Jupyter_Notebook_Installation/assets/152424908/b23dbc60-38b2-44ea-bf1d-ad8c18fdee67" width=350>
</p>

- To select a theme, use the following command:

      jt -t [theme_name]
