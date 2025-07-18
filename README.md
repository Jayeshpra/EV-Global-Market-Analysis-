# Project Overview

This project presents a comprehensive analysis of the global Electric Vehicle (EV) market, focusing on both cars and two/three-wheelers. The analysis uses historical data from 2010 to 2024 and explores the evolution of EV sales, EV stock, and adoption patterns across different powertrains – Battery Electric Vehicles (BEVs), Plug-in Hybrid Electric Vehicles (PHEVs), and Fuel Cell Electric Vehicles (FCEVs).

Interactive visualizations were created using Plotly to uncover trends in:
Year-wise global EV sales and stock
Powertrain-wise comparison (BEV, PHEV, FCEV)
Comparison between cars and two-wheelers

# Types of Vehicles:

Cars

Two & Three-Wheelers (mainly focusing on two-wheelers)

# Key Parameters:

1. EV Sales
2. EV Stock
3. EV Sales Share
4. EV Stock Share
5. Powertrain Types (BEV, PHEV, FCEV)

# Visualizations

The project includes the following visual plots:
1. BEV, PHEV, FCEV Sales Over Time (Cars & Two-Wheelers)
2. Total Sales vs Total Stock (Cars & Two-Wheelers)
3. BEV Stock vs Sales Growth
4. Cars vs Two-Wheelers Comparison (Sales & Stock)
5. These visualizations help understand how EV adoption has evolved and where it's heading globally.


# Tools & Technologies Used

1. Python 3
2. Pandas
3. NumPy
4. Plotly (for interactive visualization)
5. Matplotlib (for legacy plotting)


Two-wheelers dominate global BEV sales due to affordability and urban mobility demands.

BEV car sales are growing rapidly post-2018, showing increased adoption.

The sales gap between cars and two-wheelers is narrowing.

Total EV stock is increasing steadily in both segments, with significant growth in car stock since 2020.

Install the required libraries:
```python
pip install pandas numpy plotly matplotlib
```

Run the Jupyter Notebook or Python scripts:
```python
jupyter notebook
```
Make sure the required CSV datasets are in the correct folders (EV Data/Global/ etc.)


# Folder Structure
```
ev-global-market-analysis/
├── EV_Global_Market_Analysis.ipynb
├── EV Global Data/
│   ├── Global_Cars.csv
│   └── Global_TwoWheeler.csv
└── README.md
```


# Conclusion
This project gives a data-driven view of the EV market transition and powertrain shift. It provides valuable insights for researchers, businesses, and policymakers looking to understand trends and make informed decisions in the global EV ecosystem.
