# Fuzzy logic tutorial

This course introduces the use of fuzzy logic algorithms in Python, utilizing the
[`SciKit-Fuzzy`](https://scikit-fuzzy.github.io/scikit-fuzzy/) library.

## Requirements

Ensure you have at least Python 3.8 installed on your system.

## Installation

> [!NOTE]
> This guide assists in setting up JupyterLab and Python dependencies. 
> If you're already comfortable with Python, feel free to use your preferred setup process.

* Fork and clone this repository, or download it manually to your computer.

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
