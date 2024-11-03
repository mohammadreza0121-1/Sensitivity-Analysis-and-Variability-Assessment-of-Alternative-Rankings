# Sensitivity Analysis and Variability Assessment of Alternative Rankings

## Overview
This project focuses on performing a **sensitivity analysis** and **variability assessment** for a set of alternatives based on various parameters. The project employs graphical representations to analyze how changes in certain parameters affect the ranking and scores of alternatives, providing insights into the stability and reliability of rankings under different conditions.

The main objectives are:
- To evaluate the **standard deviation** of scores for each alternative, indicating the variability of rankings.
- To conduct a **sensitivity analysis** across different parameters, showing how the rank of each alternative changes with varying values.
- To provide insights into the internal relationships among parameters, demonstrating how the inclusion or exclusion of these relationships impacts the results.

## Project Structure

- **Standard Deviation Plot**: A bar chart showing the standard deviation of scores for each alternative, helping to identify alternatives with high variability.
- **Sensitivity Analysis**: Multiple line plots showing the rank or final score of each alternative as a function of parameter \( P \).
  - **With Internal Relationships**: Sensitivity analysis considering the internal dependencies among parameters.
  - **Without Internal Relationships**: Sensitivity analysis excluding the internal dependencies to observe isolated effects.
  
## Key Features

- **Standard Deviation Analysis**: Calculates and visualizes the variability in scores for each alternative to assess stability.
- **Parameter-Based Sensitivity Analysis**:
  - Evaluates how ranks of alternatives change with respect to parameter \( P \), both with and without internal parameter relationships.
  - Highlights the robustness of each alternative's ranking under different scenarios.
- **Graphical Insights**:
  - Provides detailed visualizations that allow easy interpretation of the impact of parameter variations on alternative rankings.

## Usage

1. **Run Jupyter Notebook**:
   - Open `main.ipynb` to load the dataset and execute the sensitivity analysis code.
   
2. **Generate Plots**:
   - Plots are automatically generated and saved, illustrating standard deviation, sensitivity with internal relationships, and sensitivity without internal relationships.

3. **Interpret Results**:
   - Use the plots to understand how sensitive each alternative’s ranking is to parameter variations and to identify alternatives with stable or fluctuating scores.

## Results

This analysis helps in understanding the robustness of the ranking process for a given set of alternatives. By examining both standard deviation and sensitivity, we gain valuable insights into the stability of rankings and the degree to which changes in parameters influence decision-making.

## License
This project is licensed under the MIT License.
