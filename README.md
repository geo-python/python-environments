# Using mamba to create the Geo-Python environment

## Starting steps
This briefly describes how to install a Python virtual environment for the Geo-Python course.

1. Install micromamba from [https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html](https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html).
2. Clone the course Python environments from GitHub
    ```bash
    git clone https://github.com/geo-python/python-environments.git
    ```
3. Change into the working directory with the cloned environment files
    ```bash
    cd python-environments
    ```

## Creating the environment
1. Create the python environment using mamba
    ```bash
    micromamba env create -f geo-python.yml
    ```
2. Activate the new environment and update JupyterLab
    ```bash
    micromamba activate geo-python
    ```
