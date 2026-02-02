# Decline Curve Analysis (DCA)

## Overview
This project performs **Decline Curve Analysis (DCA)** using Python to analyze oil and gas production data. It specifically focuses on the **Exponential Decline** model to forecast future performance and estimate reserves.

The analysis is conducted in a Jupyter Notebook, which processes production data, calculates decline parameters, and generates visualization plots for interpretation.

## Features
- **Exponential Decline Model**: Fits production data to the standard exponential decline equation.
- **Data Visualization**: Generates key performance curves:
  - **Production Rate vs. Time** (Exponential Production Decline Curve)
  - **Production Rate vs. Cumulative Production**
  - **Exponential Decline Analysis** plots
- **Automated Calculations**: Uses Python libraries to handle large datasets and compute decline rates efficiently.

## Project Structure
- `code.ipynb`: The main Jupyter Notebook containing the logic, calculations, and plotting code.
- `requirements.txt`: List of Python dependencies required to run the project.
- **Output Plots**:
  - `Exponential Decline analysis.png`
  - `Exponential Production Decline Curve.png`
  - `Production Rate and Cumulative Production .png`

## Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/5AIhil/Decline-Curve-Analysis.git](https://github.com/5AIhil/Decline-Curve-Analysis.git)
   cd Decline-Curve-Analysis
    ```
2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```  

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook code.ipynb
   ```
2. Run the cells sequentially to perform the analysis and generate plots.
3. The generated plots will be saved in the project directory.

## Tech Stack

1. Python
2. Pandas (Data manipulation)
3. NumPy (Numerical calculations)
4. Matplotlib (Plotting and visualization)

## Author
Created by 5AIhil

## License
This project is licensed under the MIT License - see the LICENSE file for details.
