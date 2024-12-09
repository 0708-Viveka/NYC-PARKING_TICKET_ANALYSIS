Parking Tickets Analysis:
Project Overview
This project analyzes the factors that influence the number of parking tickets issued in New York City across different fiscal years. By leveraging large datasets, we identify trends, correlations, and features contributing to the increase or decrease in parking violations. The project provides visualizations and insights into patterns such as monthly ticket distributions, state registrations, violation codes, and geographic impact.

Objectives:
Understand trends in parking tickets: Analyze how ticket volumes fluctuate over time.
Identify influential factors: Determine which features (e.g., violation codes, locations, times) are associated with higher or lower ticket counts.
Provide actionable insights: Highlight key areas where parking enforcement or policy adjustments might be most impactful.

Data Sources:
Data consists of parking violations issued in NYC for the fiscal years 2014–2017. Each dataset includes attributes such as:

Issue Date: Date when the violation was issued.
Violation Code: Specific parking infraction category.
Violation Description: Details of the violation.
Registration State: State where the violating vehicle was registered.
Vehicle Information: Including make, body type, and year.
Location Information: Precincts and counties.

Key Features Analyzed
Monthly Trends:

Tickets are distributed unevenly across months, with October recording the highest counts.
Visualized through bar plots to highlight monthly ticket volumes.
State Registration Impact:

A significant proportion (~77.85%) of tickets were issued to vehicles registered in New York, followed by New Jersey and Pennsylvania.
Insights into state-specific enforcement patterns.
Violation Codes:

Certain violation codes are associated with a disproportionately high number of tickets.
A bar plot demonstrates the frequency of tickets for each code, emphasizing priority areas for enforcement.
County-Specific Analysis:

Counties such as Manhattan and Brooklyn see higher ticket volumes.
Geographic insights inform localized policy-making.
Insights
Time-Based Trends:

Specific months, days, and times see higher ticket issuance. Understanding these trends can help improve public awareness and compliance.
Common Violations:

Recurring violation codes suggest potential gaps in compliance or clarity of parking rules.
Geographic Patterns:

Counties with high violation densities indicate areas where parking management may need enhancement.
Vehicle and State Trends:

The dominance of tickets for NY-registered vehicles reflects enforcement bias or driver habits.
Tools & Libraries Used
Data Manipulation: Pandas, Dask
Visualization: Matplotlib, Seaborn
Computation: Google Colab for cloud-based analysis

