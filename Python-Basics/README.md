# Python Basics

This folder contains introductory Python exercises created while setting up my data analytics learning environment. 

## Files 

- `hello_world.py` - First Python script, prints "Hello, world!"
- `pandas_intro.ipynb` - Basic introduction to reading data information using pandas

## How to Run

### Running Python Scripts

To run `hello_world.py` from the terminal: 

```bash
python3 hello_world.py
```

On some systems it may be necessary to instead run:

```bash
python hello_world.py
```

Make sure you are in the `Python-Basics` folder when running this command.

### Running Jupyter Notebooks

To run `pandas_intro.ipynb` without using any IDE extension:

1. Start Jupyter in the folder:

```bash
jupyter notebook
```

2. Open `pandas_intro.ipynb` in the [browser](http://localhost:8888)

3. Run the cells sequentially to see the outputs

To run `pandas_intro.ipynb` with IDE extension:

1. Press `Run All` play button at the top of the notebook file or run each cell sequentially

## Dataset

This Jupyter project uses the [Titanic dataset](https://raw.githubusercontent.com/pandas-dev/pandas/main/doc/data/titanic.csv) from the pandas documentation.

The dataset is including in the `/data` folder for convenience.

## Dependencies

Requires Python3 and depends on the packages listed in `requirements.txt`.

### Setup

1. **Create and activate a virtual environment:**

```bash
python3 -m venv venv
source venv/bin/activate
```

2. **Install project dependencies:**
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

3. **Install Jupyter (if not already installed and no IDE extension is used):**
```bash
pip install notebook
```

Note: To deactivate the virtual environment when done:
```bash
deactivate
```

## Purpose

- Practice Python syntax and basics
- Learn data 
- Prepare for later data analysis projects and dashboards