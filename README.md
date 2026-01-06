# Learning-Data-Science

This repository contains data science projects and experiments completed in our college laboratory using Jupyter Notebook.

## Table of Contents
- [Installing Jupyter Notebook](#installing-jupyter-notebook)
- [Setting up Jupyter Notebook in VS Code](#setting-up-jupyter-notebook-in-vs-code)
- [Using Anaconda for Jupyter Notebook](#using-anaconda-for-jupyter-notebook)
- [Installing Required Libraries](#installing-required-libraries)
- [Running the Notebooks](#running-the-notebooks)

## Installing Jupyter Notebook

### Windows

1. Install Python from [python.org](https://www.python.org/downloads/) (Python 3.8 or higher recommended)
2. Open Command Prompt and run:
```bash
pip install jupyter notebook
```
3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

### macOS

1. Install Python (usually pre-installed, or install via [python.org](https://www.python.org/downloads/))
2. Open Terminal and run:
```bash
pip3 install jupyter notebook
```
3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

### Linux

1. Open Terminal and update your package manager:
```bash
sudo apt update  # For Ubuntu/Debian
```
2. Install pip if not already installed:
```bash
sudo apt install python3-pip
```
3. Install Jupyter Notebook:
```bash
pip3 install jupyter notebook
```
4. Launch Jupyter Notebook:
```bash
jupyter notebook
```

## Setting up Jupyter Notebook in VS Code

### Prerequisites for All Operating Systems

1. Install [Visual Studio Code](https://code.visualstudio.com/)
2. Install the Python extension from the VS Code marketplace (search for "Python" by Microsoft)
3. Install the Jupyter extension from the VS Code marketplace (search for "Jupyter" by Microsoft)

### Setting up Virtual Environment

#### Windows

1. Open Command Prompt or PowerShell in your project directory
2. Create a virtual environment:
```bash
python -m venv venv
```
3. Activate the virtual environment:
```bash
venv\Scripts\activate
```
4. Install Jupyter in the virtual environment:
```bash
pip install jupyter notebook
```

#### macOS

1. Open Terminal in your project directory
2. Create a virtual environment:
```bash
python3 -m venv venv
```
3. Activate the virtual environment:
```bash
source venv/bin/activate
```
4. Install Jupyter in the virtual environment:
```bash
pip install jupyter notebook
```

#### Linux

1. Open Terminal in your project directory
2. Create a virtual environment:
```bash
python3 -m venv venv
```
3. Activate the virtual environment:
```bash
source venv/bin/activate
```
4. Install Jupyter in the virtual environment:
```bash
pip install jupyter notebook
```

### Using Jupyter Notebooks in VS Code

1. Open VS Code and open your project folder
2. Open or create a `.ipynb` file
3. Click on the kernel picker in the top right corner
4. Select your virtual environment (it should appear as `venv` or the name you gave it)
5. Start writing and executing code cells

## Using Anaconda for Jupyter Notebook

Anaconda is a distribution that comes with Jupyter Notebook and many data science libraries pre-installed.

### Installing Anaconda

#### Windows, macOS, and Linux

1. Download Anaconda from [anaconda.com](https://www.anaconda.com/download)
2. Run the installer and follow the installation instructions
3. After installation, launch Anaconda Navigator or use the terminal/command prompt

### Launching Jupyter Notebook via Anaconda

#### Using Anaconda Navigator
- Open Anaconda Navigator
- Click on the "Launch" button under Jupyter Notebook

#### Using Terminal/Command Prompt
```bash
jupyter notebook
```

### Creating a Conda Environment

1. Open Anaconda Prompt (Windows) or Terminal (macOS/Linux)
2. Create a new environment:
```bash
conda create -n datalab python=3.10
```
3. Activate the environment:
```bash
conda activate datalab
```
4. Install Jupyter in the environment:
```bash
conda install jupyter
```

## Installing Required Libraries

This repository uses the following Python libraries: matplotlib, numpy, pandas, plotly, and scikit-learn.

### Using pip (Standard Python or Virtual Environment)

Make sure your virtual environment is activated (if using one), then run:
```bash
pip install matplotlib numpy pandas plotly scikit-learn
```

### Using Anaconda/Conda

If you're using Anaconda, activate your conda environment first, then run:
```bash
conda install matplotlib numpy pandas plotly scikit-learn
```

Or install them individually:
```bash
conda install matplotlib
conda install numpy
conda install pandas
conda install plotly
conda install scikit-learn
```

### Verifying Installation

You can verify that the libraries are installed correctly by running the following in a Python shell or Jupyter Notebook:
```python
import matplotlib
import numpy
import pandas
import plotly
import sklearn

print("All libraries imported successfully!")
```

## Running the Notebooks

1. Clone this repository:
```bash
git clone git@github.com:shlok2006-cd/Learning-Data-Science.git
cd Learning-Data-Science
```

2. Set up your environment and install the required libraries (see sections above)

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Navigate to the desired notebook file (`.ipynb`) and open it

5. Run the cells sequentially by pressing `Shift + Enter` or using the "Run" button

---

## Contributing

Feel free to contribute to this repository by submitting pull requests or opening issues for any problems you encounter.


---

**Note**: Make sure you have a stable internet connection when installing packages, and ensure your Python version is 3.8 or higher for compatibility with all libraries. The repository is not fully completed multiple changes will be applied so hope you are updated on any changes on the repository ;)
