# tum-ai-multiclass-classification

This Python project, called "tum-ai-multilabel-classification," provides implementations of preprocessing and modeling of a multiclass classification problem on synthetic data.

## Setup

To run the project, you need to follow these steps:

### Step 1: Install Python 3.11.0 with pyenv

1. Install `pyenv`, a Python version management tool, if you haven't already. You can find installation instructions at the [pyenv GitHub repository](https://github.com/pyenv/pyenv#installation).
2. Once `pyenv` is installed, open a terminal and run the following command to install Python 3.11.0:

   ```shell
   pyenv install 3.11.0
   ```

   This command will download and install Python 3.11.0.

### Step 2: Set up a Virtual Environment

1. Install `pyenv-virtualenv`, a pyenv plugin to manage virtual environments. On MacOS you can install `pyenv-virtualenv` using homebrew:

   ```shell
   brew install pyenv-virtualenv
   ```

   You can find additional installation steps at the [pyenv-virtualenv repository](https://github.com/pyenv/pyenv-virtualenv).

2. Once `pyenv-virtualenv` is installed, navigate to your project's root directory using the terminal and create a virtual environment named "multiclass" by running the following command:

   ```shell
   cd tum-ai-multiclass-classification/
   pyenv virtualenv 3.11.0 multiclass
   pyenv local multiclass
   ```

   This command will create a new directory named "multiclass" that contains the isolated Python environment. It will be activated automatically on navigation into the tum-ai-multiclass-classification directory, if you have followed all the `pyenv-virtualenv` installation steps.

### Step 3: Install Poetry

1. Install `poetry`, a dependency management and packaging tool for Python projects:

    Linux, MacOS, Windows(WSL)

   ```shell
   curl -sSL https://install.python-poetry.org | python3 -
   ```

### Step 4: Install Dependencies

1. With the virtual environment activated, navigate to the project's root directory in the terminal if you're not already there.
2. In the project's root directory, you'll find a file named `poetry.lock`. This file contains the project's dependencies and their specific versions.
3. Run the following command to install all dependencies specified in the `poetry.lock` file:

   ```shell
   poetry install
   ```

   This command will fetch and install all required dependencies for the project.

## Running the Project

After completing the setup steps, you can run the project. Make sure the virtual environment is activated before running any code.

To run the project, execute the necessary Python scripts or import the modules you want to use into your own Python scripts.

For example, if you have a script named `example.py` that uses the Scratch project's functions, you can run it using the following command:

```shell
python example.py
```

## License

The Scratch project is open-source and released under the [MIT License](LICENSE). Feel free to use, modify, and distribute it according to the terms of the license.