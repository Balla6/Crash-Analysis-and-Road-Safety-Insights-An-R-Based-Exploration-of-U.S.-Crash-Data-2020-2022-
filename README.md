# **Crash Analysis and Road Safety Insights: An R-Based Exploration of U.S. Crash Data (2020–2022)**

## **Introduction**
This project analyzes crash data from the Crash Report Sampling System (CRSS) using RStudio to uncover patterns and trends influencing road safety in the United States from 2020–2022. The analysis focuses on identifying demographic, environmental, and behavioral factors contributing to crashes and providing actionable insights to improve road safety.

## **Objectives**
1. Analyze crash severities (fatal, serious injury, minor injury, no apparent injury) and their distributions.
2. Explore demographic patterns (age, gender) in crash participation.
3. Investigate how weather conditions and urbanicity (urban vs. rural) impact crash outcomes.
4. Examine crash trends over time and during peak hours.
5. Develop actionable recommendations for improving road safety.

---

## **Key Findings**
- **Crash Severity**:
  - "No Apparent Injury" accounted for 46% of crashes, while fatal crashes made up 2.37%, mostly in rural areas.
  
- **Demographics**:
  - Drivers aged 20–29 were the most involved in crashes.
  - Male drivers were significantly overrepresented compared to female drivers.
  
- **Weather**:
  - Clear weather conditions accounted for 72.74% of crashes, likely due to reduced vigilance during favorable weather.
  
- **Urban vs. Rural**:
  - Urban areas had more crashes overall, but rural areas experienced a higher proportion of fatal and severe injuries.

- **Peak Crash Hours**:
  - Crashes peaked during commuting hours (7–9 AM and 3–6 PM) due to increased traffic volume.

---

## **Technologies Used**
- **RStudio**: Main development environment.
- **Programming Language**: R
- **Libraries Used**:
  - `tidyverse` (Data manipulation and visualization)
  - `lubridate` (Date and time handling)
  - `scales` (Data scaling for plots)
  - `viridis` and `RColorBrewer` (Color palettes)
  - `ggplot2` (Visualization)

---

## **How to Run the Project**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Balla6/big-data-crash-analysis.git
   cd big-data-crash-analysis
