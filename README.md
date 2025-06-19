# Healthcare Patients Analytical Report

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Installation](#installation)
- [How to Use This Dashboard](#how-to-use-this-dashboard)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [Technical Details](#technical-details)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)


## Overview

The **Healthcare Patient's Analytical Dashboard** provides a comprehensive overview of patient statistics. It is designed to help healthcare administrators and decision-makers analyze patterns in patient visits, satisfaction levels, and service delivery. This dashboard provides insights into various aspects of patient interactions and outcomes, enabling improvements in healthcare services.


## Key Features

1. **Total Patients Overview:** This displays the total number of patients and provides a breakdown of Administration Appointments versus Non-Administration Appointments.
2. **Average Satisfaction Score:** Patient feedback, including the percentage of services not rated.
3. **Average Wait Time:** Highlights time management performance.
4. **Visit Breakdown by Week Type:** Analyzes patient visits by weekday and weekend.
5. **Patient Demographics:** Categorized patients into age group and percentages of gender breakdown(male, female, unknown/others).
6. **Patient Visit Trends:** Identifies peak patient visits by month and shows a steady increase in patients by year.
7. **Referral Insights:** A clear visualization of whether the patient is referred to a specific department(General Practice, Orthopedics, Physiotherapy, Cardiology, etc.) or a walk-in visitor.
8. **Satisfaction and Wait Time Heatmap:** Highlights average wait times & average satisfaction for patients based on race, with a color-coded heatmap that can be switched through the Combobox.
9. **Period Analysis:** Allows filtering by AM and PM periods for time-based insights.


## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/tshihab/Healthcare-Patients-Analytical-Report.git
    ```
2. **Navigate to the project directory:**

    ```bash
    cd Healthcare-Patients-Analytical-Report
    ```
3. Load the Data: Load the data into your visualization tool and ensure the data fields align with the visualizations.
4. Run the Dashboard: If using Power BI, open the .pbix file to view and interact with the dashboard.


## How to Use This Dashboard

1. **Filters:** Use slicers like Periods (AM/PM) or department-specific data to focus on specific metrics.
2. **Visuals:** Examine trends through line charts (e.g., visits by month, year) and compare categories with bar charts and heatmaps.
3. **Interpret Insights:** Identify areas of improvement (e.g., wait times, satisfaction) and allocate resources based on department demand.


## Insights

- Average waiting time of patients
- Monthly patient visit
- Total Visit by department
- Patients visit  by age group
- Average Satisfaction by age group and patient race
- Average waiting time by age group and patient race


## Recommendation

- **High Wait Times:** Long wait times among certain racial groups need further investigation and corrective action.
- **Satisfaction Improvement:** Low average satisfaction scores indicate an opportunity to improve patient care and communication.
- **Peak Demand:** The surge in visits during mid-year months suggests the need for increased staffing and resources in that period.


## Technical Details

- **Visualization Tool:** Power BI
- **Data Source:** Hospital ER.csv
- **Interactivity:** Slicers enable dynamic filtering for personalized analysis.


## Future Enhancements

- Incorporate geographic data to analyze trends by location.
- Include predictive analytics to forecast patient volume.
- Add metrics for staff efficiency and resource utilization.


## Contributing

Contributions are welcome! Please feel free to submit a pull request.


## License

This project is licensed under the [MIT License](LICENSE).
