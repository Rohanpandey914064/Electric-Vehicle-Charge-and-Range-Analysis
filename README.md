# Visualization Tool for Electric Vehicle Charge and Range Analysis

## 🚀 Live Project
Access the live application here:  
https://electric-vehicle-charge-and-range-cnc5.onrender.com/


## Introduction

Electric Vehicles (EVs) are rapidly transforming the transportation industry as countries focus on reducing carbon emissions and promoting sustainable mobility. With the increasing number of EV models and charging stations, analyzing EV data becomes important to understand trends related to vehicle performance, charging infrastructure, efficiency, and pricing.

This project focuses on building a **data visualization platform using Tableau** to analyze electric vehicle data. The system presents insights through **interactive dashboards, visualizations, and data stories**, helping users explore EV-related trends easily.

The dashboard is further **integrated into a web application using Flask**, allowing users to interact with the visualizations through a browser.

-

# Project Development Procedure

## 1. Data Collection and Extraction from Database

### Overview
Data collection is the process of gathering and measuring information on variables of interest in a structured manner. This allows us to analyze patterns, test assumptions, and generate insights from the dataset.

The dataset used in this project includes information about:

- Electric vehicle models
- Vehicle brands
- Powertrain types
- Vehicle efficiency
- Charging stations in India
- Vehicle price
- Top speed

### Dataset Acquisition
The dataset required for the Tableau project was collected and verified to ensure it is:

- Clean and structured
- Relevant to EV analysis
- Suitable for visualization
- Free from inconsistencies

### Storing Data in Database
After collecting the dataset, it was stored in a **MySQL database** for better management.

SQL operations were used to:

- Filter unnecessary records
- Clean incomplete or duplicate entries
- Transform and structure the dataset
- Organize the dataset into tables

This ensured the dataset was ready for analysis and visualization.

### Connecting Database with Tableau
The next step involved connecting the database to **Tableau**.

This connection allows Tableau to:

- Access the stored dataset
- Retrieve data for analysis
- Update visualizations dynamically

---

# 2. Data Preparation

### Overview
Data preparation ensures that the dataset is clean, structured, and ready for visualization.

Even when datasets appear clean, additional preparation helps maintain **accuracy and consistency**.

### Data Review and Exploration
The dataset was explored to understand its structure.

This included:

- Reviewing column names
- Checking data types
- Understanding value ranges
- Identifying outliers

### Filtering and Structuring Data
The dataset was filtered based on analysis needs, such as:

- Selecting specific EV models
- Filtering by regions
- Focusing on relevant vehicle specifications

### Field Renaming and Formatting
Column names were adjusted to make them easy to understand inside Tableau.

Additional formatting steps included:

- Converting date fields
- Ensuring numerical fields were correctly recognized
- Standardizing naming conventions

### Calculated Fields
Some **calculated fields** were created to support deeper analysis.

Examples include:

- **Count** – counts the number of EV models
- **Count_PowerTrain** – counts vehicles based on powertrain type

### Data Validation
Finally, the dataset was validated by comparing summary metrics with the source data to ensure accuracy.

---

# 3. Data Visualization

### Overview
Data visualization converts raw data into graphical representations that make patterns and trends easier to understand.

Using **Tableau**, multiple visualizations were created.

### Visualizations Created

1. Charging Stations by Region and Type in India  
2. EV Charging Stations Map of India  
3. Different EV Cars in India  
4. Top Speed for Different Brands  
5. Price Comparison for Different EV Cars  
6. Top 10 Most Efficient EV Brands  
7. Brands Categorized by Body Style  
8. Brand Analysis by PowerTrain Type  
9. Number of Models by Each Brand  
10. Summary Card for EV Brands Globally  
11. Summary Card for EV Brands in India  

Each visualization highlights specific insights related to electric vehicles and charging infrastructure.

---

# 4. Dashboard Development

### Overview
A dashboard is a graphical interface that organizes multiple visualizations into a single view.

It helps users quickly understand key insights and interact with the data.

### Dashboard Design
The dashboard was designed to be:

- Clear and organized
- Responsive across screen sizes
- Easy to navigate
- Visually consistent

### Interactive Filters

**Body Style Filter**

Allows filtering cars based on body types such as:

- Cabrio
- Hatchback
- Liftback
- MPV
- Pickup
- Sedan
- SUV
- Station

**Brand Filter**

Allows users to analyze data for specific EV brands such as:

- Tesla
- BMW
- Audi
- Tata
- Hyundai
- Mercedes
- Porsche

**PowerTrain Filter**

Allows filtering vehicles based on drivetrain types:

- AWD (All Wheel Drive)
- FWD (Front Wheel Drive)
- RWD (Rear Wheel Drive)

---

# 5. Data Story Creation

### Overview
A data story presents insights in a narrative format that helps users understand the analysis step by step.

### Tableau Story Scenes

A story in Tableau consists of multiple **scenes**, where each scene highlights a specific insight.

Each scene includes:

- A visualization
- Supporting explanation
- Key insights derived from the data

This helps users follow the analysis in a logical sequence.

---

# 6. Performance Testing

### Overview
Performance testing ensures the dashboard runs efficiently without overloading the system.

### Data Rendering Evaluation
The volume of data being rendered from the database was monitored using **MySQL Workbench**.

Important checks included:

- Table size
- Number of rows
- Column structure

### Filter Optimization
Filters were optimized to:

- Reduce unnecessary data processing
- Improve dashboard responsiveness
- Allow targeted analysis

### Visualization Complexity Monitoring
The number of visualizations and calculated fields was monitored to ensure smooth performance.

---

# 7. Web Integration

### Overview
The final step involved integrating the Tableau dashboard into a web application.

This allows users to access the visualizations through a browser interface.

### Publishing the Dashboard
The Tableau workbook was published using **Tableau Public**.

Steps followed:

1. Prepare the final dashboard
2. Remove unnecessary sheets or data
3. Sign in to Tableau Public
4. Save and publish the workbook

After publishing, Tableau generates a **public link to the dashboard**.

### Embedding Dashboard into Web Application
A simple web interface was developed using **Flask**.

The Tableau dashboard was embedded into the web application using the **embed code** provided by Tableau Public.

Users can now:

- Access dashboards online
- Apply filters
- Explore visual insights interactively

---

# Tools and Technologies Used

- Tableau
- MySQL
- SQL
- Python
- Flask
- Tableau Public

---

# Conclusion

The **Visualization Tool for Electric Vehicle Charge and Range Analysis** demonstrates how data visualization can transform raw EV data into meaningful insights.

By combining:

- Database management
- Data preparation
- Tableau visualizations
- Interactive dashboards
- Web integration with Flask

the system provides an intuitive platform for exploring electric vehicle data and understanding trends in electric mobility.
