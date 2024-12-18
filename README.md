# Project Overview

This project is part of the [PwC Switzerland Power BI Virtual Case Experience](https://www.theforage.com/simulations/pwc-ch/power-bi-cqxg?ref=W5vwWAjutTpHbEraC), demonstrating the application of digital tools in data visualization, automation, and data cleansing to address key business challenges. It features a series of Power BI dashboards focusing on Call Centre Trends, Customer Retention, and Diversity & Inclusion. These dashboards provide actionable insights into various aspects of business operations, helping PwC Switzerland and its clients enhance efficiency, strengthen customer loyalty, and foster inclusivity.

Through detailed data analysis and visualization, this project aims to support data-driven decision-making, identify improvement opportunities, and drive innovation across critical areas of business strategy and operations.

![Uploading image.png…](https://www.influentialsoftware.com/wp-content/webp-express/webp-images/uploads/2024/09/V1-2-1-900x450.jpg.webp)

# Installation and Usage Instructions

# Installation

Power BI Desktop is required to view and interact with the dashboards. If not already installed, it can be downloaded from the [official Microsoft Power BI website](https://www.microsoft.com/en-us/power-platform/products/power-bi/desktop). Installation instructions are provided on the site.

# Usage

The .pbix files associated with each dashboard are hosted within this repository. After installing Power BI Desktop, download the .pbix files from the repository and open them with Power BI Desktop. The data sources are embedded within the files, eliminating the need for additional setup to explore the visualizations. Users can navigate through the dashboards using the tabs at the bottom of the Power BI interface to explore different visualizations and insights.

To download the .pbix files, navigate to the folder in this repository where they are stored, select a file, and use the 'Download' button. Cloning or downloading the entire repository is an alternative method for accessing all files.

![image](https://github.com/user-attachments/assets/a6a92aa5-265a-4b0d-a574-1c63aae9c968)

# 📌  Scenario

At PwC, we empower global organizations while upskilling our 276,000 employees, equipping them to thrive in the digital era. Our mission is to enable everyone to learn, work, and innovate with cutting-edge digital tools. Employees can become "Digital Accelerators," advancing their expertise in areas like data analytics, automation, AI, and digital storytelling by mastering self-service tools and coding languages and applying these skills in real-world scenarios.


Your manager, Giulia, will mentor you through your Power BI upskilling journey, helping you become a data expert and Digital Accelerator. A key client has already reached out, seeking your expertise in visualizing their data, paving the way for impactful insights and solutions.

**Call Center Analysis | Pwc Switzerland Power BI Virtual Case Experience**

![image](https://github.com/user-attachments/assets/180f4374-ea45-41be-905e-a41026775072)

**This virtual experience program consists of 3 tasks:**

Task 1: Call Centre Trends Create Dashboard - Visualizing  & agent behaviour.
Task 2: Customer Retention - create a dashboard that visualizes customer demographics and insights.
Task 3: Diversity & Inclusion.

# Table of contents
* Data Sourcing
* Problem Statement
* Data Preparation
* Data Modeling
* Data Visualization
* Analysis and Insights

# Data Sourcing

The dataset used for this analysis was sourced from [Pwc Switzerland](https://www.theforage.com/simulations/pwc-ch/power-bi-cqxg) and available dataset's here below.
* Task 1. [Call Center Dataset](https://github.com/mroyalreddy07/Microsoft-Power-BI-PWC-PowerBI-Virtual-Case-Experience/blob/main/Call-Center-Dataset.xlsx)
* Task 2. [Churn Dataset](https://github.com/mroyalreddy07/Microsoft-Power-BI-PWC-PowerBI-Virtual-Case-Experience/blob/main/Churn-Dataset.xlsx)
* Task 3. []()

# Problem Statement

**Problem**
* The manager at PhoneNow telecom company seeks actionable insights from the call center dataset to understand customer satisfaction and agent performance trends over time.  
* A telecom manager requires transparency and analysis of call center data to identify long-term patterns in customer interactions and agent efficiency.  
* The manager at a major telecom firm is looking to analyze call center data for clear insights into customer behavior and agent performance over the long term.  

**Object** 
  Design a Power BI dashboard for Claire showcasing key performance indicators (KPIs) and metrics. Ensure it provides clear insights into customer    
  satisfaction, agent performance, and call center trends.
  
- Interactive display of call trends and patterns.  
- Overview of agent performance and behaviors.  
- Summary of customer satisfaction metrics.  
- Comprehensive visuals for business discussions and deeper analysis.  
- Minimal interaction required for ease of use.  

**Possible KPIs** include (to get you started, but not limited to):

* Overall customer satisfaction
* Overall calls answered/abandoned
* Calls by time
* Average speed of answer
* Agent’s performance quadrant -> average handle time (talk duration) vs calls answered

# Data Preparation

The dataset was imported into Microsoft Power BI Desktop for analysis. It underwent transformation in Power Query and was modeled for effective visualization.

# Data Cleaning
  The process of cleaning the dataset was completed in Power Query with the following steps.

* Unnecessary columns were removed.
* Each of the columns in the table was validated to have the correct data type.
* Unnecessary rows were removed

# Data Transformation
  The process of converting, cleaning, and structuring data into a usable format that can be analyzed to support decision making processes, and to propel the growth of an organization.
  an additional column named Satisfaction Likert was created for referencing using the M-formula:
  
# Data Modeling
  Once the dataset was cleaned and transformed, it was ready for modeling. However, as it contained only a single table, the data modeling process was minimal.
  
# Data Visualization

# Task 1

**Call Centre Trends**
  The first dashboard provides an in-depth look at call center performance metrics, including customer satisfaction, call volumes, and agent efficiency, helping to highlight opportunities for operational           enhancements.

  Acess [here](https://github.com/mroyalreddy07/Microsoft-Power-BI-PWC-PowerBI-Virtual-Case-Experience/blob/main/Call_Center.pbix) for live and interactive dashboards.
     
  ![Screenshot 2024-12-18 143824](https://github.com/user-attachments/assets/015ffcf6-fe66-4b45-8e44-5afa63db17bf)

# Task 2

**Customer Retention**
  Designed to support the telecom client's goal of enhancing gender balance at the executive level, this dashboard highlights key diversity and inclusion metrics. It provides actionable insights into trends,       progress, and areas requiring attention
  
  Discover live, actionable dashboards [here]()
  
# Measures
  The measure used in visualization are:
  
 * **Calculated measures**

  * Answered = CALCULATE(COUNT(Call_Center[Call Id]),FILTER(Call_Center,Call_Center[Answered (Y/N)]="Y"))
  * Resolved(Y) = CALCULATE(COUNT(Call_Center[Call Id]),FILTER(Call_Center,Call_Center[Resolved] ="Y"))

# Analysis and Insights
  The goal of this dashboard is to enable managers to explore the data independently, but I have outlined some key points of interest below.

  



