<h1 align="center">🏨 Hotel Reservation Analysis</h1>

## 📊 Project Overview

This project presents a comprehensive **Exploratory Data Analysis (EDA)** of hotel booking data, analyzing **119,390 records** across **32 attributes** for two types of hotels. The analysis uncovers key insights into booking patterns, customer behavior, and factors that influence hotel reservations.

## 🎯 Business Objective

**Explore and analyze hotel booking data to discover important factors that govern bookings and provide actionable insights for hotel management.**

## 🔍 Problem Statement

- **When is the best time of year to book a hotel room?**
- **What is the optimal length of stay to minimize costs?**
- **How do booking patterns vary between different hotel types?**
- **What factors influence booking cancellations?**

## 📈 Analysis Highlights

- **Data Visualization** - Interactive charts and graphs revealing booking trends
- **Descriptive Statistics** - Comprehensive statistical analysis of booking patterns  
- **Correlation Analysis** - Identifying relationships between key variables
- **Data Aggregation** - Grouping and summarizing data for deeper insights

## 🛠️ Techsack

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red.svg)](https://matplotlib.org/)

```python
# Core Libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

# Analysis Tools
- Jupyter Notebook
- Python 3.8+
- Pandas for data manipulation
- Matplotlib & Seaborn for visualization
```

## 📁 Project Structure

```
Hotel-Reservation/
│
├── Hotel Reservation Report.ipynb      # Main Report NoteBook
├── Hotel Reservation Cancellation ML.ipynb         # Cancellation Prediction ML NoteBook
├── Hotel Reservation EDA.ipynb         # Main Analysis NoteBook
├── LICENSE                             # General Github License
├── README.md                           # Project documentation
└── Data                                # Dataset files
    ├── Raw Data                        # Raw / Unfiltered Dataset files
    │   ├── Hotel Reservations.csv      # Old Hotel Reseracation Data
    │   └── Hotel booking(in).csv       # Updated Hotel Reservation Data
    ├── clean_data.csv                  # clean_Dataset
    └── New Data                        # New Dataset folders consist of Fraction of the original clean data into multiple fields
        ├── booking_party_data.csv      # Consist of Individual booking Party / guest data 
        ├── cancellation_data.csv       # Consist of Booking Cancellation data 
        ├── date_time_data.csv          # Consist of Date related field data 
        ├── fact_bookings.csv           # Consist of Every Booking related data 
        ├── guest_data.csv              # Consist of Overall Guest data 
        ├── hotel_data.csv              # Consist of Hotel data 
        └── room_data.csv               # Consist of Individual Room data 
```

## 🚀 Getting Started

### Pre-Requisites
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Running the Analysis
1. Clone this repository
2. Open `Hotel Reservation Report.ipynb` in Jupyter Notebook
3. Run all cells to reproduce the analysis

## 📊 Key Findings

The analysis reveals critical insights into:
- **Seasonal booking patterns** and peak demand periods
- **Customer segmentation** based on booking behavior
- **Cancellation trends** and their impact on revenue
- **Optimal pricing strategies** for different hotel types

## 🎨 Visualizations

The notebook includes comprehensive visualizations covering:
- Time series analysis of booking trends
- Distribution plots of key metrics
- Correlation heatmaps
- Customer behavior patterns

## 👨‍💻 Author

**Rishabh Salian**
- Project Type: Complete EDA Project Complete analysis and insights
- Contribution: Individual 

## 📝 License

This project is open source and available under the [GPL 3.0 LICENSE](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

---

⭐ **Star this repository if you found it helpful!**

📧 **Questions?** Feel free to reach out for any clarifications or discussions about the analysis.
