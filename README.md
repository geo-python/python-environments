# Using mamba to create the Geo-Python environment

## Starting steps
This briefly describes how to install a Python virtual environment for the Geo-Python course.

1. Install mambaforge from [https://docs.conda.io/en/latest/miniconda.html](https://github.com/conda-forge/miniforge#mambaforge).
2. Clone the course Python environments from GitHub
    ```bash
    git clone https://github.com/geo-python/python-environments.git
    ```
3. Change into the working directory with the cloned environment files
    ```bash
    cd python-environments
    ```

## Creating the environment for students
1. Create the python environment using mamba
    ```bash
    mamba env create -f geo-python-student.yml
    ```
2. Activate the new environment and update JupyterLab
    ```bash
    conda activate geo-python-student
    sh postBuild
    ```

## Creating the environment for teachers
1. Create the python environment using mamba
    ```bash
    mamba env create -f geo-python-teacher.yml
    ```
2. Activate the new environment and update JupyterLab
    ```bash
    conda activate geo-python-teacher
    sh postBuild
    ```
