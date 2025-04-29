# Aircraft Risk Assessment for Investment

## Project Overview
This project analyzes aviation accident data to identify aircraft types associated with the lowest statistical risk. The goal is to inform strategic decisions for a company's new aviation division, supporting both private and commercial aircraft acquisition.

The analysis leverages accident reports from the National Transportation Safety Board (NTSB) and transforms the data into actionable insights through Python and Tableau.

## Objectives
Through comprehensive data analysis, this project aims to:
- Uncover key factors contributing to aircraft accident risk.
- Identify low-risk aircraft models based on historical accident data.
- Provide actionable insights to support data-driven investment decisions in aviation.
- Mitigate risks and ensure a safer and more profitable entry into the aviation industry.

## Business Understanding
With the company expanding into the aviation sector, minimizing investment risk is critical. By understanding which aircraft are historically safer and the circumstances under which accidents are more likely to occur, the aviation division can make informed purchasing decisions that prioritize safety and profitability.

# Tools Used
- Python (Pandas, Matplotlib, Seaborn) – Data cleaning, analysis, and visualization
- Jupyter Notebook / VS Code – Coding environment
- Tableau – Interactive dashboards and charts
- Git & GitHub – Version control and collaboration


## Data Understanding and Analysis
- **Datasets Used**:  
  - `AviationData.csv`: Contains detailed records of aviation accidents.
  - `USState_Codes.csv`: Provides state code mappings for regional analysis.  
  *(Both are located in the `Data/` directory.)*

- **To replicate the analysis**:
  1. Install the required libraries:  
     `pip install -r requirements.txt`
  2. Open the notebook:  
     `aviation_analysis.ipynb`
  3. Run the cells in sequence to explore the data and visualizations.

## Visualizations Included
The following visualizations are included both in the Jupyter Notebook and the project presentation slides:
1. **Accident Trends Over Time**: ShowS the Accident Trends Over Time (Year vs. Number of Accidents).
2. **Purpose of Flight vs Fatalities**: visualizes the fatalities in the various types of flights showing the riskiest Flight Types.
3. **atalities per Aircraft Model**: shows the Top 10 Aircraft Models with the Lowest Risk.

## Interactive Dashboard
Explore the insights interactively via Tableau:  
👉 [Aviation Accident Dashboard](https://public.tableau.com/app/profile/catherine.maina)
This dashboard provides an engaging overview of accident trends, aircraft risk levels, and regional or seasonal patterns.

## Recommendations
- **Consider Aircraft with a low Accident rate**
- **Align Investment with Use-Case Insights (Purpose of flight)**
- **Prioritize Aircraft Models with No or Minimal Fatalities**
- **Consider Aircraft that have shown to have the least damage**


## Conclusion

This analysis highlights clear differences in aircraft safety across models and use cases. The findings support strategic decisions by recommending aircraft with lower fatality and damage rates, particularly those suited for commercial or charter operations. These insights offer a data-driven foundation for the company's aviation investment plans.


## Contact
For questions or feedback, reach out to:  
📧 **katemaina22@gmail.com**