# Simon's Algorithm Quantum Project

This project implements Simon's algorithm using a quantum virtual environment. There are a few different files - 
- example.ipynb shows a single run of the quantum circuit
- fullAlgorithm.ipynb runs the full quantum algorithm, and solves for the string
- walkthrough.ipynb constructs the quantum circuit, explaining each step.


## Installation

To set up the project, run the following commands:

```sh
# Clone the repository
git clone https://github.com/szarobsky/Simons

# Navigate to the project directory
cd Simons

# Set up the virtual environment
python -m venv venv

# Activate the virtual environment
source venv/bin/activate  # On Unix or MacOS
# or
venv\Scripts\activate.bat  # On Windows

# Install the dependencies
pip install -r requirements.txt
```

## Configuration

1. Obtain your IBM Quantum API key from the [IBM Quantum Experience](https://quantum-computing.ibm.com/).

2. Save your IBM Quantum account credentials using the following Python code:
    ```python
    from qiskit_ibm_runtime import QiskitRuntimeService

    # Save an IBM Quantum account.
    QiskitRuntimeService.save_account(channel="ibm_quantum", token="YOUR_IBM_QUANTUM_TOKEN")
    ```

    Replace `"YOUR_IBM_QUANTUM_TOKEN"` with your actual IBM Quantum API token.

## Usage

To run the project, execute the main script:
```sh
python main.py
```