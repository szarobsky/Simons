# Simon's Algorithm Quantum Project

This project implements Simon's algorithm using a quantum virtual environment. There are a few different files - 
- example.ipynb shows a single run of the quantum circuit
- fullAlgorithm.ipynb runs the full quantum algorithm, and solves for the string
- walkthrough.ipynb constructs the quantum circuit, explaining each step

## Installation

Check if git is installed:
```sh
git --version
```
If not, check out [git installation](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

Check Python version:
```sh 
python3.12 --version
```
If Python 3.12.4 is not installed, check out [Python 3.12.4](https://www.python.org/downloads/release/python-3124/).

Check pip version:
```sh
pip --version
```
If pip is not installed, check out [pip installation](https://pip.pypa.io/en/stable/installation/).

If pip is installed, but not pip 24.2, run:
```sh
python -m pip install --upgrade pip==24.2
```

Check virtualenv version:
```sh
virtualenv --version
```
If virtualenv 20.26.6 is not installed, run:
```sh
pip install virtualenv==20.26.6
```

To set up the project, run the following commands:

```sh
# Clone the repository
git clone https://github.com/szarobsky/Simons

# Navigate to the project directory
cd Simons

# Set up the virtual environment
virtualenv -p python3.12.4 venv

# Activate the virtual environment
source venv/bin/activate  # On Unix or MacOS
# or
venv/Scripts/activate  # On Windows

# Install the dependencies
pip install -r requirements.txt
```
