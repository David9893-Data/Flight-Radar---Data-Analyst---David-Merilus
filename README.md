# ✈️ Flight Performance Dashboard – Global Airlines Report

## Context  
Air travel is a critical industry where delays can lead to cascading effects on passengers, operations, and costs. This project was created as part of a business intelligence case study to explore flight performance on a global scale.

The dashboard aims to provide a detailed overview of flight activities using real-world-inspired data, structured across several relational tables and analyzed with Power BI.

## Objective  
The main goal was to identify patterns and performance issues related to airline operations and punctuality. Through this project, I wanted to simulate the kind of real-time reporting a data analyst would be expected to deliver in an enterprise setting.

## Key Insights  
- **5M flights** had delays greater than 15 minutes, out of **14M** total flights.
- The **average delay rate per airline** is around **0.40** (40% of flights delayed).
- The **average number of passengers per flight** is **108.42**, with some variation across airlines.
- A few airlines like *NetJets*, *Sky Regional*, and *Servicios Aero Personal* appear more frequently among delayed flights.
- **Geographic mapping** shows wide global coverage and helps identify congestion patterns at airports.

## Challenges & Approach  
- Data was distributed across several tables (`flights_info`, `airlines`, `airports`, `planes`, `delay`, etc.), requiring **data modeling** before analysis.
- Handling **time-based metrics** and setting up proper **relationships** between date and delay dimensions was essential for temporal analysis.
- The dashboard includes **filtering by airport, country, and time**, ensuring interactivity for different stakeholders (e.g., airline managers, airport operators).

## Recommendations  
- Airlines with higher delay counts should **investigate causes** (maintenance, staffing, route congestion) and prioritize improvements.
- Airports with frequent high passenger loads could **optimize turnaround times** or review scheduling to reduce cumulative delays.
- Implement a **predictive delay model** for flights using historical trends (not covered here but could be the next phase).
- Consider adding **weather or seasonality variables** to further explain delay fluctuations.

## Why This Project Matters  
This case reflects the reality of working with large, relational datasets in Power BI and turning them into actionable insights. It highlights not only technical skills (DAX, modeling, visual storytelling) but also analytical thinking when it comes to making data speak.
