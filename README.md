# Simon's Algorithm Quantum Project

This project implements Simon's algorithm using a quantum virtual environment.

## Installation

### Prerequisites

1. **Git**: Check if Git is installed:
    ```sh
    git --version
    ```
    If not, check out [Git installation](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

2. **Python**: Check Python version:
    ```sh 
    python3.12 --version
    ```
    If Python 3.12.4 is not installed, check out [Python 3.12.4](https://www.python.org/downloads/release/python-3124/).

3. **Pip**: Check pip version:
    ```sh
    pip --version
    ```
    If pip is not installed, check out [pip installation](https://pip.pypa.io/en/stable/installation/).

    If pip is installed, but not pip 24.2, run:
    ```sh
    python -m pip install --upgrade pip==24.2
    ```

4. **Virtualenv**: Check virtualenv version:
    ```sh
    virtualenv --version
    ```
    If virtualenv 20.26.6 is not installed, run:
    ```sh
    pip install virtualenv==20.26.6
    ```

### Setup

To set up the project, run the following commands:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/szarobsky/Simons
    ```

2. **Navigate to the project directory**:
    ```sh
    cd Simons
    ```

3. **Set up the virtual environment**:
    ```sh
    virtualenv -p python3.12.4 venv
    ```

4. **Activate the virtual environment**:
    - On Unix or MacOS:
        ```sh
        source venv/bin/activate
        ```
    - On Windows:
        ```sh
        venv/Scripts/activate
        ```

5. **Install the dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

## Project Structure
- `example.ipynb`: Jupyter notebook showing a single run of the quantum circuit.
- `fullAlgorithm.ipynb`: Jupyter notebook that runs the full quantum algorithm and solves for the secret string.
- `walkthrough.ipynb`: Jupyter notebook that constructs the quantum circuit, explaining each step.
- `requirements.txt`: Lists the project's dependencies.
- `.gitignore` Specifies files and directories to be ignored by Git.