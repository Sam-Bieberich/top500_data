# Top500 Data

This repository holds all of the Top500 data from the site up to November 2024 in Excel and CSV formats.

## Instructions for Running Jupyter Notebooks

To run the Jupyter notebooks in this repository, follow these steps:

1. **Install Jupyter Notebook**:
    Ensure you have Jupyter Notebook installed. You can install it using pip:
    ```bash
    pip install notebook
    ```

2. **Navigate to the Notebooks Directory**:
    Change your directory to where the notebooks are located. For example:
    ```bash
    cd /c:/VSCode/360/top500_data/notebooks
    ```

3. **Run Jupyter Notebook**:
    Start the Jupyter Notebook server:
    ```bash
    jupyter notebook
    ```

4. **Open the Notebooks**:
    In the Jupyter interface, open the following notebooks in order:
    - `csv_generation.ipynb`
    - `csv_merge.ipynb`
    - `csv_clean.ipynb`

5. **Execute the Cells**:
    For each notebook, run the cells sequentially to execute the code. You can do this by clicking on each cell and pressing `Shift + Enter`.

Make sure you have all the necessary dependencies installed as specified in the notebooks. The version of python used in testing was 3.11.9 via Visual Studio Code. 