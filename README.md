# Energy Consumption Analysis

## Project Overview

This project analyzes energy consumption data from two buildings: the Lecture Block and the Academic Block. The goal is to compare their total energy usage and visualize trends over time.

## Data Description

The dataset consists of time-series energy consumption readings for both buildings. The columns in the CSV files represent:

- **Timestamp (Epoch format)**: The time at which the energy reading was recorded.
- **Energy Consumption**: The total energy usage at the given timestamp.

## Features

- **Data Loading & Preprocessing**: Reads CSV files and assigns meaningful column names.
- **Total Energy Consumption Analysis**: Computes and compares the total energy consumption of both buildings.
- **Data Visualisation**: Generates graphs to display energy usage trends.

## Technologies Used

- **Python**
- **Pandas**: For data handling and analysis.
- **Matplotlib**: For data visualisation.

## How to Run the Project
1. **Clone the repository**:

   ```bash
   git clone <repository-url>
2. **Install the required dependencies:**
   ```bash
   pip install pandas matplotlib
3. **Run the analysis script:**
   ```bash
   After opening the jupyter notebook **analysis.ipynb** at the top of the file press **Run All**
## Expected Output
- A summary of total energy consumption for both buildings.
- A graph comparing the energy consumption trends over time.

## Future Improvements
- Add interactive visualisations.
- Incorporate more buildings into the analysis.
