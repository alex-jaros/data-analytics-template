# Script Folder

## Overview
The `script/` folder contains reusable Python scripts and utility functions that support the analysis and modeling in the project. This folder helps modularize the code, keeping the notebook clean and focused on analysis.

## Folder Purpose
This folder is intended to store scripts for tasks such as data preprocessing, custom functions, and modeling pipelines. By centralizing reusable scripts here, it ensures consistency and promotes code reuse across the project.

## Contents
- **Data Preprocessing Scripts**: Scripts to clean, transform, and preprocess raw data.
- **Custom Functions**: Python modules containing helper functions used across notebooks.
- **Modeling Scripts**: Code for setting up and training models.

## Guidelines for Adding Scripts
1. **File Naming**:
   - Use descriptive filenames (e.g., `data_cleaning.py`, `model_pipeline.py`).
   - Group related functionality in a single file if possible.

2. **Documentation**:
   - Add clear comments and docstrings in your scripts to explain the functionality of functions and classes.
   - Update this `README.md` with a brief description of any new scripts added.

3. **Code Quality**:
   - Follow PEP 8 style guidelines for Python code.
   - Test scripts thoroughly before adding them here.

## Example Files
- `data_cleaning.py`: Contains functions for handling missing data, normalizing values, and encoding categorical variables.
- `visualization_helpers.py`: Includes reusable functions for generating plots and visualizations.
- `model_pipeline.py`: Implements a pipeline for data splitting, model training, and evaluation.

## Notes
- Scripts in this folder should focus on reusable, general-purpose tasks. If a script is highly specific to a single notebook, it can remain within that notebook.
- Ensure all dependencies used in the scripts are documented in the `requirements.txt` file.

