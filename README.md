# Shor's Algorithm - Quantum Computing Course Project

This repository contains a Jupyter Notebook implementing Shor's Algorithm, which was developed as part of my quantum computing course. Shor's Algorithm is a quantum algorithm for integer factorization, which runs exponentially faster than the best-known classical algorithms.

## Project Structure

- `shor_algorithm.ipynb`: The main Jupyter Notebook containing the implementation of Shor's Algorithm.
- `requirements.txt`: A list of Python libraries required to run the notebook.
- `token.txt` and `token_loaded.txt`: Files used for managing IBM Quantum Experience tokens.

## Setup Instructions

### 1. Create and Activate a Virtual Environment

It is recommended to use a virtual environment to manage dependencies. You can create and activate a virtual environment using the following commands:

```sh

# Install viertualenv if not already installed
pip install virtualenv

(Windows)

# Create a virtual environment
python -m venv <name-viertualenv>

# Activate the virtual environment 
.\venv\Scripts\activate

# install dependency
pip install -r requirements.txt

# start notebook with browser
jupyter notebook

# start notebook without browser
jupyter notebook --no-browser