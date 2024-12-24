# Vehicle Behavior Analysis Tool
This project provides a tool to analyze and compare the characteristics of vehicle behavior. The workflow is implemented using JupyterLab, specifically in `main.ipynb`.

## Features
- Classifies vehicle behavior data based on user-defined keywords.
- Cleans data by removing outliers and correcting biases.
- Builds models using LightGBM for vehicle behavior analysis.
- Compares vehicle behaviors under identical conditions.

## Requirements
- Python
- JupyterLab

## How to Use
1. Open JupyterLab
2. Open `main.ipynb`.
3. Set the following paths in the notebook:
   - Data file
   - PLT file
4. Define keywords to classify the data.
4. Run all cells in the notebook.

## Workflow
1. **Set Paths and Keywords**:  
   Specify the paths to the data and PLT files, and define keywords for data classification.
2. **Data Classification**:  
   Classify data into groups based on the specified keywords.
3. **Data Cleaning**:  
   Convert measurement data into CSV format, load it into a DataFrame, and clean the data by removing outliers and correcting biases.
4. **Model Creation**:  
   Build predictive models using LightGBM for each classified dataset.
5. **Behavior Comparison**:  
   Simulate vehicle behavior under identical conditions for all models and compare the results.

## Results
The tool outputs comparison plots and reports that highlight differences in vehicle behavior across the classified data groups.