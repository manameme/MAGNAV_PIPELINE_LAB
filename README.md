# MAGNAV_PIPELINE_LAB
## Environment

This project is run inside an isolated Python environment.  
Current development uses a **Conda environment** (Python 3.10).

### Create and activate (Conda)
```bash
conda create -n mammal310 python=3.10
conda activate mammal310
python -m pip install --upgrade pip
```
=======

### Install project dependencies

Install the required Python packages for the MagNav pipeline using pip.
Make sure the Conda environment is activated before running this command.
```bash
pip install -r requirements.txt
```

### Jupyter Notebook setup
Jupyter Notebook is used to run and explore the MagNav pipeline notebooks.
Install it inside the activated Conda environment.
```bash
pip install notebook
```

Launch Jupyter Notebook
Start Jupyter Notebook from the project root directory
```bash
jupyter notebook
```

### Running the notebooks
Navigate to the notebooks/ directory in the Jupyter interface.

Open Notebook 01 and run all cells from top to bottom.

After Notebook 01 completes, continue running the remaining notebooks in numerical order.

