# ML-PDF-Miner

## Overview
In this project, we aim to build a machine learning model to solve a specific problem using the power of data analysis and predictive modeling. We will be leveraging the Python programming language along with the popular data manipulation library pandas and the machine learning library Scikit-learn.

## Usage
To use this project, follow these steps:
1. Clone the repository: `git clone https://github.com/matheusinit/ml-pdf-miner.git`
2. Navigate to the project directory: `cd ml-pdf-miner`
3. Make the steps for Installation described below

## Installation
To run this project, you will need to have Python installed on your machine.

### Virtual Environment Setup
To ensure a clean and isolated environment for this project, it is recommended to set up a virtual environment using Python's `virtualenv` package. Follow these steps to create and activate a virtual environment:

1. Install `virtualenv` if you haven't already:
  ```
  pip install virtualenv
  ```

2. Create a new virtual environment:
  ```
  virtualenv venv
  ```

3. Activate the virtual environment:
  - For Windows:
    ```
    venv\Scripts\activate
    ```
  - For macOS and Linux:
    ```
    source venv/bin/activate
    ```

4. Install the required dependencies:
  ```
  pip install -r requirements.txt
  ```

Now you have a virtual environment set up and ready to use for this project.

## Project Structure
The project structure is as follows:
- `data/`: This directory contains the dataset used for training and testing the machine learning model.
- `src/`: This directory contains the source code of the project.
  - `00_pdf_text_extraction.py`: This Jupyter Notebook provides the text extraction from PDF files using Python.
  <!-- - `preprocessing.py`: This script handles data preprocessing tasks.
  - `model.py`: This script defines and trains the machine learning model.
  - `evaluation.py`: This script evaluates the performance of the trained model. -->

## Contributing
If you would like to contribute to this project, feel free to submit a pull request. We welcome any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
