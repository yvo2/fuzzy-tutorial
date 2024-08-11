# Fuzzy logic tutorial

This course introduces the use of fuzzy logic algorithms in Python, utilizing the
[`SciKit-Fuzzy`](https://scikit-fuzzy.github.io/scikit-fuzzy/) library.

## Requirements

Python version 3.9, 3.10, or 3.11 (3.12 not yet supported).

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
python3 -m venv venv
```

3. Activate the virtual environment:

```bash
source venv/bin/activate
```

### Windows setup

For Windows, it is recommended to use Windows Subsystem for Linux (WSL) and apply the same steps from above.

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

### Docker

If you encounter issues with the setup above, you can use [Docker](https://docs.docker.com/get-docker/) to run the environment.

1. Build the Docker Image

This command will build a Docker image and install the necessary libraries:

```bash
docker build -t fuzzy-notebook:latest .
```

2. Run the Docker Container:

Use the following command to start the JupyterLab server in a Docker container:

```bash
docker run -it --rm -p 10000:8888 -v "${PWD}":/home/jovyan/work fuzzy-notebook:latest
```

3. Access JupyterLab:

Open your browser and go to http://localhost:10000/lab?token=YOUR_TOKEN_IN_CONSOLE. 
Replace `YOUR_TOKEN_IN_CONSOLE` with the token displayed in your terminal after running the container. 


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