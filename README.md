# Fuzzy logic tutorial

This course introduces the use of fuzzy logic algorithms in Python, utilizing the
[`SciKit-Fuzzy`](https://scikit-fuzzy.github.io/scikit-fuzzy/) library.

## Requirements

Python version 3.9, 3.10, or 3.11

## Installation

> [!NOTE]
> This guide assists in setting up JupyterLab and Python dependencies. 
> If you're already comfortable with Python, feel free to use your preferred setup process.

First, fork and clone this repository, or download it manually to your computer. 
Then open a terminal inside the repository and proceed.

### Linux / macOS setup

1. Verify your Python version:

```bash
python3 --version
```

2. Create a virtual environment:

```bash
python3 -m venv virenv
```

3. Activate the virtual environment:

```bash
source virenv/bin/activate
```

### Windows setup

1. Verify your Python version:

```bash
python --version
```

2. Create a virtual environment:

```shell
python -m venv virenv
```

3. Activate the virtual environment:

```bash
virenv\Scripts\activate
```

### Installing libraries

With the virtual environment activated, install the required dependencies:

```bash
pip install --upgrade pip
pip install -r requirements.txt
pip install jupyterlab
```

To start JupyterLab:

```bash
jupyter lab
```

This command should open a local web interface for JupyterLab, where you can access the tutorial notebooks.


## Tutorials

This course includes two tutorial notebooks:

* **01_FuzzyControlSystem.ipynb**: Introduction to fuzzy control systems.
* **02_FuzzyClustering.ipynb**: Introduction to fuzzy clustering techniques.

Work through these notebooks in order.

## Deliverable

After completing the tutorials, create your own Jupyter notebook applying one of the approaches to a problem.

1. **Select a domain**: choose a domain related to your group project (if already available) or a personal interest. 
2. **Create and name your notebook**: experiment with the chosen approach and save your notebook as `03_<YourProjectName>.ipynb`. 
3. **Push to your repository**: upload your completed notebook to your GitHub repository