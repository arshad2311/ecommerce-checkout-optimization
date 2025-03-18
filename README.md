# E-commerce Checkout Process Optimization using Web Analytics Project

This project demonstrates an analysis and optimization of an e-commerce checkout process using web analytics principles.  It is designed to showcase skills in business process analysis, information systems design, and data-driven decision-making for application to the International Business Information Systems BSc program at Furtwangen University.

## Project Structure

The project is organized as follows:

*   `simulated_store/`: Contains a simplified HTML/CSS/JS simulated e-commerce store to demonstrate the checkout process.
*   `data_generation/`: Includes a Python script (`generate_checkout_data.py`) to generate simulated checkout session data in CSV format.
*   `web_analytics_integration/`: Contains an example JavaScript file (`analytics_snippet.js`) demonstrating how web analytics tracking could be integrated (simulated).
*   `data_analysis_visualization/`: Includes a Python script (`analyze_checkout_data.py`) to analyze the simulated data and generate visualizations (funnel chart, completion rates chart). Also includes a basic HTML dashboard (`dashboard.html`) to display the visualizations.
*   `report/`: Contains a Markdown template (`project_report_template.md`) for writing the project report.
*   `README.md`: This file, providing an overview of the project.

## How to Run (Simplified Demonstration)

1.  **Generate Simulated Data:** Run the Python script `data_generation/generate_checkout_data.py`. This will create a file named `simulated_checkout_data.csv` in the `data_generation` folder.  **Make sure you have Python and pandas installed (`pip install pandas matplotlib seaborn`).**
2.  **Analyze Data and Generate Visualizations:** Run the Python script `data_analysis_visualization/analyze_checkout_data.py`. This script will:
    *   Load the `simulated_checkout_data.csv` file.
    *   Perform basic funnel analysis and calculate step completion rates.
    *   Generate PNG image files for the funnel chart and step completion rates chart in the `data_analysis_visualization` folder.
    *   Print completion messages to the console.
3.  **View the Dashboard:** Open the file `data_analysis_visualization/dashboard.html` in your web browser. This will display a very basic HTML dashboard showing the generated charts.
4.  **Simulated Store:** Open `simulated_store/index.html` in your web browser to interact with the simulated e-commerce store checkout process. Observe the console log for simulated analytics events.
5.  **Write Project Report:**  Use the `report/project_report_template.md` as a starting point to write your comprehensive project report, detailing your methodology, findings, recommendations, and reflections.

**Note:** This is a simplified demonstration project.  For a real-world application, you would use a real web analytics tool, analyze real website data, and implement more robust data analysis and visualization techniques.  The `web_analytics_integration` and simulated store are for illustrative purposes to demonstrate the concepts.

---
