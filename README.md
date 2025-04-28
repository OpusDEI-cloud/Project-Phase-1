# Aircraft Safety Analysis for Acquisition Decisions

## Project Overview
This project aims to analyze aviation accident data to identify aircraft types that pose the lowest risk. The insights generated will aid the company's new aviation division in making informed decisions about aircraft purchases for commercial and private operations.

## Objectives
- Identify aircraft types with the lowest risk profiles based on historical accident data.
- Analyze geographical and seasonal patterns in aviation accidents.
- Provide actionable recommendations to minimize risk and maximize safety.

## Data Sources
1. **AviationData.csv**: Contains aviation accident data from 1962 to 2023, covering both domestic and international incidents.
2. **USState_Codes.csv**: Provides a mapping between US state names and their corresponding codes for geographical analysis.

## Key Features
- **Incident Severity**: A feature engineered to classify accidents into low, medium, and high severity based on injuries and aircraft damage.
- **Aircraft Risk Factor**: A calculated metric representing the relative risk of each aircraft type based on the frequency of incidents.
- **Geographical Analysis**: Insights into accident frequencies by state and location.
- **Seasonal Trends**: Analysis of accident patterns across different months of the year.

## Tools and Technologies
- **Python**: For data cleaning, analysis, and visualization.
- **Pandas**: For data manipulation and feature engineering.
- **Seaborn & Matplotlib**: For creating visualizations.
- **Jupyter Notebook**: For interactive data analysis and documentation.

## Key Findings
- **Aircraft with Lowest Risk**: Identified aircraft types with the lowest average incident severity and risk.
- **Geographical Hotspots**: States like California, Texas, Florida, Alaska, and Arizona have the highest accident frequencies.
- **Seasonal Patterns**: July has the highest number of accidents, indicating potential seasonal risks.

## Recommendations
1. **Prioritize Aircraft with Established Safety Records**: Focus on aircraft types with consistently low accident rates and minimal severity.
2. **Implement Regional Risk Assessments**: Tailor aircraft selection and operational procedures to mitigate risks specific to high-risk regions.
3. **Develop a Comprehensive Aircraft Evaluation Framework**: Incorporate factors like maintenance history, operational costs, and technological advancements into the decision-making process.

## Limitations
- Missing data in key fields like location and aircraft details.
- Lack of information on flight hours and distance flown for better risk assessment.
- Potential biases in data collection and reporting.

## Next Steps
- Gather more comprehensive data, including flight hours, aircraft age, and maintenance records.
- Refine feature engineering to improve the accuracy of risk and severity metrics.
- Explore external data sources to validate findings and enhance analysis.

## How to Run the Project
1. Clone the repository.
2. Ensure the required datasets (`AviationData.csv` and `USState_Codes.csv`) are in the `Data/` directory.
3. Open the Jupyter Notebook file `Phase 1 Project Analysis.ipynb`.
4. Run the cells sequentially to reproduce the analysis and visualizations.
## 📊 Interactive Dashboard

Explore the interactive dashboard [here](https://public.tableau.com/app/profile/raphael.ragot/viz/Phase1ProjectInteractiveDashboard/Dashboard1).


## Contact
For any questions or feedback, please contact the project team at ragotraphael@gmail.com