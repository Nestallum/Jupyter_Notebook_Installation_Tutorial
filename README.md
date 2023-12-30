# Jupyter Notebook Installation Tutorial

This repository aims to simplify the process of downloading and installing Jupyter Notebook, an interactive computing platform in the Python language. Whether you are a beginner or an experienced user, these detailed instructions guide you through the setup of your Jupyter Notebook environment. The guide covers both Anaconda and standalone installations. Additionally, I provide instructions on how to apply themes to enhance the appearance of your Jupyter Notebook interface.

## Python
To use Jupyter Notebook, you'll need Python installed on your machine.

### Download Python:
- Go to the official Python website: https://www.python.org/downloads/

-  Select the Python version most suitable for your operating system (Windows, macOS, or Linux). It's recommended to choose the latest version unless there are specific reasons for using an older version.

-  Download the installer and follow the instructions to install Python on your machine. **Make sure to check the "Add Python to PATH" option during installation.**

### Verify the Installation:

- Open a terminal (Command Prompt on Windows, Terminal on macOS/Linux). Type the following command to check that Python is installed correctly:

        python --version
   
You should see the version of Python you just installed.

### Update pip (Python package manager):

- Type the following command to update pip:

        python -m pip install --upgrade pip

- To check the version:

        pip --version
  
Now that Python is installed, you're ready to use the pip command to install Jupyter Notebook.

## Jupyter Notebook with Anaconda
To get Jupyter Notebook, simply install Anaconda, which comes with the complete distribution, inclusive of essential tools such as Jupyter Notebook. Once Anaconda is installed, you'll also benefit from additional utilities like Anaconda Navigator, facilitating the management of virtual environments, packages, and other tools integrated into the distribution.

### Download Anaconda:
-  Go to the official Anaconda website: https://www.anaconda.com/download
-  Download the installer and follow the instructions to install Anaconda on your machine.

After installing Anaconda, you have access to a variety of tools:
<p align="center">
<img src="https://github.com/Nestallum/Jupyter_Notebook_Installation/assets/152424908/b7b6e36a-010a-4d64-b8dc-35cd53982401">
</p>

### Launch Jupyter Notebook:
To launch Jupyter Notebook, you can either click on the Jupyter Notebook app, and it will open in your browser automatically. 

Alternatively, you can open a terminal and enter the following command:

        jupyter notebook
        
## Jupyter Notebook without Anaconda
Alternatively, you have the option to install Jupyter Notebook independently without relying on Anaconda.

- Install the classic Jupyter Notebook with:

      pip install jupyter
  
This will install Jupyter Notebook on your system, allowing you to use it without the need for the entire Anaconda distribution.

- To run the notebook:

      jupyter notebook

## Jupyter Notebook Themes
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

  
You can now take full advantage of Jupyter Notebook and its beautiful theme! 👍
