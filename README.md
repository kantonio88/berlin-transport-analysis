
# Berlin Public Transport Analysis 🚇

## Overview
This project analyzes simulated public transport data in Berlin to uncover patterns in passenger volumes and delays. It is a beginner-friendly demonstration of how Python can be used for data cleaning, analysis, and visualization.

![Project Status](https://img.shields.io/badge/Project%20Status-Completed-green)

## Objectives
- **Understand passenger flow**: Analyze the number of passengers across various routes.
- **Delay analysis**: Examine delays at different stations and during various times.
- **Visual storytelling**: Use visualizations to communicate key insights.

## Tools Used
- **Python Libraries**:
  - `pandas` for data manipulation.
  - `matplotlib` for visualizations.

## Dataset
- **Source**: Simulated data
- **Columns**:
  - `Route`: The transport route (e.g., U1, U2).
  - `Station`: Major Berlin stations.
  - `Passenger_Count`: Number of passengers.
  - `Delay_Minutes`: Delay in minutes.
  - `DateTime`: Timestamp of the record.

## Key Insights
1. **Passenger Trends**:
   - Route **U4** has the highest average passenger count.
2. **Delay Analysis**:
   - Average delays are minimal (~1.2 minutes) across all stations.
3. **Hourly Trends**:
   - Passenger volumes peak during **morning and evening commute hours**.

## Folder Structure
```
berlin-transport-analysis/
│
├── berlin_transport_analysis.ipynb  # Jupyter notebook with analysis
├── data/
│   └── Berlin_Transport_Data.csv    # Simulated dataset
└── README.md                        # Project documentation
```

## Future Work
- **Incorporate real-world data**: Replace simulated data with public Berlin transport datasets.
- **Expand analysis**: Include weather effects or ticketing data for richer insights.
- **Interactive dashboard**: Use tools like Tableau or Power BI for interactive visualizations.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/kantonio88/berlin-transport-analysis.git
   ```
2. Navigate to the folder:
   ```bash
   cd berlin-transport-analysis
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook berlin_transport_analysis.ipynb
   ```
4. Run the cells to see the analysis and visualizations.

## Acknowledgments
This project was created for learning and demonstration purposes.
