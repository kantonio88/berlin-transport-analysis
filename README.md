
# Berlin Public Transport Analysis 🚇

## Overview
This project analyzes simulated public transport data in Berlin to uncover patterns in passenger volumes and delays. The goal is to demonstrate beginner-friendly data analysis and visualization techniques using Python. Insights from this analysis could support city planning and optimize commuter experiences.

![Project Status](https://img.shields.io/badge/Project%20Status-Completed-green)

## Project Status
This project is complete as a foundational demonstration of data analysis skills, with plans for potential future enhancements

## Objectives
- **Understand passenger flow**: Analyze passenger numbers across various routes.
- **Delay analysis**: Examine delays at different stations and during various times.
- **Visual storytelling**: Use data visualizations to effectively communicate insights.

## Tools Used
- **Python Libraries**:
  - `pandas` for data manipulation.
  - `matplotlib` for visualizations.
 - **Jupyter Notebook**: As the coding environment.

## Dataset
- **Source**: Simulated public transport data.
- **Columns**:
  - `Route`: Transport route (e.g., U1, U2).
  - `Station`: Major Berlin stations.
  - `Passenger_Count`: Number of passengers.
  - `Delay_Minutes`: Delay in minutes.
  - `DateTime`: Timestamp of the record.

## Key Insights
1. **Passenger Trends**:
   - Route **U4** consistently has the highest average passenger count.
2. **Delay Analysis**:
   - Average delays across all stations are minimal, approximately 1.2 minutes.
3. **Hourly Trends**:
   - Passenger volumes peak during **morning and evening commute hours**, highlighting rush-hour trends.

## Folder Structure
```
berlin-transport-analysis/
│
├── berlin_transport_analysis.ipynb  # Jupyter notebook with analysis
├── data/
│   └── Berlin_Transport_Data.csv    # Simulated dataset
└── README.md                        # Project documentation
```
## Sample Visualization
Example visualization: Passenger volumes by hour of the day, showing clear peaks during rush hours.

## Future Work
- **Incorporate real-world data**: Replace the simulated dataset with public transport data from Berlin.
- **Expand analysis**: Include additional factors like weather or ticketing data to uncover richer insights.
- **Interactive dashboard**: Use tools like Tableau or Power BI for dynamic and interactive visualizations.

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
This project was created for learning and demonstration purposes for future job interviews .
