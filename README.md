# U.S. Domestic Flights Performance Analysis (2015)

## Overview
This repository contains the files for a comprehensive data analysis project focused on **U.S. Domestic Flights Performance in 2015**. The primary goal was to analyze over 5.8 million flight records to identify patterns and key drivers of delays and cancellations, providing actionable insights for aviation industry stakeholders [1].

The analysis was performed using **Microsoft Power BI** for data preparation, modeling, and visualization.

## Project Structure
The repository is structured to ensure clarity and reproducibility:
- `reports/`: Contains the final Power BI dashboard (`.pbix`) and the full project documentation (`.pdf`).
- `data/`: Contains the `raw/` subdirectory with a `README.md` file pointing to the original Kaggle dataset source.
- `README.md`: This file, providing an overview of the project.
- `.gitignore`: Specifies files and directories that Git should ignore.
- `LICENSE`: Defines the licensing terms (MIT License).

## Key Insights & Analysis
The interactive Power BI dashboard and the full report detail the following key findings:

1.  **Temporal Patterns:** Delays accumulate throughout the day, **peaking in the evening (6 PM - 9 PM)**. The highest volume of delays occurs on **Thursdays and Fridays**, suggesting a correlation with weekend travel [1].
2.  **Airline Performance:** Legacy carriers like Delta (DL) and Alaska Airlines (AS) show better on-time performance compared to low-cost carriers. **American Eagle (MQ) was identified as having the highest cancellation rate** [1].
3.  **Airport Performance:** Major hubs such as Chicago O'Hare (ORD), Dallas/Fort Worth (DFW), and Hartsfield-Jackson Atlanta (ATL) record the highest number of total cancellations due to their high traffic volume [1].
4.  **Recommendations:** For passengers, booking **morning flights** and avoiding travel on Thursdays/Fridays is recommended to minimize delay risk [1].

## How to View the Project
1.  **Power BI Dashboard:** Download the `skylinestatsfinal.pbix` file from the `reports/` folder. You will need **Power BI Desktop** to open and interact with the dashboard.
2.  **Documentation:** The full project details, methodology, data model (Star Schema), and detailed analysis are available in the `Final_Project_DOC.pdf` file.

## Data Source
The data for this project was sourced from **Kaggle** [2]. The dataset includes three primary files: `flights.csv` (5.8M+ records), `airports.csv`, and `airlines.csv`.

## References
[1]: # "FinalProjectDOC.pdf: U.S. Domestic Flights Performance Analysis (2015) Report."
[2]: # "[https://www.kaggle.com/datasets/usdot/flight-delays]"
