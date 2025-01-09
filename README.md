# Project Title: Anomaly Detection System

## Overview
This project involves building a multi-agent system leveraging Large Language Models (LLMs) to perform anomaly detection, analysis, and reporting. The system is designed to streamline the process of identifying and summarizing anomalies in data, generating SQL queries, creating visualizations, and producing high-level insights in report format.

## Key Features
- **Anomaly Detection**: Pre-processed and grouped data anomalies by objectives to serve as inputs for agents.
- **Multi-Agent Collaboration**:
  - **Agent 1**: Generates simple plots from outlier data for initial visualization.
  - **Agent 2**: Writes SQL queries for time-series analysis of relevant columns.
  - **Agent 3**: Produces a high-level summary of the anomaly data and integrates insights into a comprehensive report.
- **Data Visualization**: Time-series data is visualized to identify trends and possible issues.
- **Automated Reporting**: Combines visuals, observations, and possible data issues into a structured report grouped by objectives.

## Tools and Technologies
- **Google Cloud Platform**: For data storage and querying.
- **Python**: To orchestrate agent collaboration and anomaly detection logic.
- **SQL**: For time-series data queries.
- **Jupyter Notebook**: For development and testing of agent workflows.
- **Visualization Libraries**: Matplotlib and Seaborn for generating plots.

## Workflow
1. **Input Data**:
   - Perform anomaly detection on the dataset prior to feeding it into the system.
   - Group the anomalies by objectives for targeted analysis.

2. **Agent 1**:
   - Takes the outlier data and generates basic visualizations (e.g., scatter plots) to highlight anomalies.

3. **Agent 2**:
   - Generates SQL queries for time-series data analysis.
   - Applies SQL to extract relevant insights from the dataset.
   - Visualizes the time-series data for trend analysis.

4. **Agent 3**:
   - Summarizes findings from Agents 1 and 2.
   - Integrates visuals and observations into a report grouped by objectives.

5. **Output**:
   - A structured report containing:
     - Visualizations.
     - Observations.
     - Identified data issues.

## Results
The system effectively automates the analysis and reporting of anomalies in time-series datasets. It provides:
- Quick visualization of outliers and trends.
- Actionable SQL queries for further analysis.
- Comprehensive, objective-based reports for decision-making.

### Sample Report Output:
- **Visuals**: Graphical representations of anomalies and trends.
- **Observations**: Summaries of findings from the analysis.
- **Possible Data Issues**: Highlighted areas requiring further investigation.

## Repository Structure
- **Linkedin_agent_V1.ipynb**: Jupyter Notebook implementing the multi-agent system and workflows.
- **Sample Screenshot**: Example output showing agent collaboration and generated report.
![Screenshot 2025-01-08 at 10 28 43 PM](https://github.com/user-attachments/assets/4d4ad5d1-865e-4264-acea-871a384b7a3c)

## Future Enhancements
- Integrate additional agents for advanced analytics such as predictive modeling.
- Automate the anomaly detection step to streamline the entire workflow.
- Enhance visualization capabilities with dynamic, interactive charts.
- Incorporate feedback loops for iterative analysis and report refinement.
