# Vessel Data Analysis Project

## Project Overview
This Python-based project analyzes maritime vessel data to uncover operational patterns in Southeast Asia. The analysis includes:
- Data cleaning and preprocessing of vessel characteristics and position data
- Vessel classification by size (Handymax, Supramax, Panamax, Capesize)
- Cargo type and destination analysis
- Geographical mapping of vessel positions in Southeast Asia
- Predictive modeling to determine cargo loading completion

VESSEL DATA ANALYSIS PROJECT - SETUP INSTRUCTIONS

1. PYTHON REQUIREMENTS
   - Python 3.8 or higher
   - Required packages (install using pip): Check requirements.txt

2. DATA FILES
   - Place these files in your project directory:
     vessel_characteristics.csv
     vessel_positions.csv

3. SETUP COMMANDS
   # Create virtual environment (recommended)
   python -m venv venv
   
   # Activate environment
   # Windows:
   venv\Scripts\activate
   # Mac/Linux:
   source venv/bin/activate
   
   # Install packages
   pip install pandas numpy matplotlib seaborn shapely plotly scikit-learn jupyter

4. RUNNING THE ANALYSIS
   - Open vessel_analysis.ipynb in VS Code
   - Install VS Code extensions if prompted:
     * Python (ms-python.python)
     * Jupyter (ms-toolsai.jupyter)
   - Select Python interpreter from your virtual environment
   - Run all cells sequentially (Ctrl+Alt+Enter or "Run All" button)

5. TROUBLESHOOTING
   - Missing data files: Ensure CSVs are in same directory as notebook
   - Package issues: Update pip first: pip install --upgrade pip
   - Plotly rendering: Install VS Code Jupyter extension
   - Virtual environment: Restart VS Code after creating venv

6. KEY FILES
   - vessel_analysis.ipynb : Main analysis notebook
   - vessel_characteristics.csv : Vessel attribute data
   - vessel_positions.csv : Positional and operational data
