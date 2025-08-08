# Insurance-Data-Analysis
Project Overview

This project involves building an interactive Power BI dashboard to analyze insurance claims data sourced from an MS SQL Server database. The goal is to provide actionable insights into claim amounts, policy statuses, customer activity, and sentiment from customer feedback.
Data Source

    Raw insurance claims dataset imported and cleaned in MS SQL Server

    Connected Power BI Desktop directly to SQL Server for live data querying and visualization

Features & Analysis

    Claim Amount by Age Group: Identify trends and patterns in claim amounts across different age segments

    Claim Status Breakdown: Visualize claims as Settled, Pending, or Rejected categorized by policy type

    Active vs. Inactive Policies: Display policy status in an easy-to-understand donut chart

    Drill-through Filters: Enable detailed exploration of individual policies and customers

    Scheduled Refresh: Automated data refresh to keep the dashboard updated

    Row-Level Security (RLS): Implemented role-based access control to ensure data privacy

    Sentiment Analysis: Analyzed customer feedback sentiment (positive, neutral, negative) for qualitative insights

Tools & Technologies

    MS SQL Server – Data storage and preparation

    Power BI Desktop & Service – Data modeling, visualization, and dashboard publishing

    DAX & Power Query – Measures, calculated columns, and data transformation

    Python (optional) – For sentiment analysis preprocessing (if applicable)

How to Use

    Open the .pbix file in Power BI Desktop

    Connect to your own instance of the SQL Server database or use sample data

    Explore the interactive reports and visuals

    Modify or extend the dashboard as needed for your use case
  
  Future Improvements

    Enhance sentiment analysis with advanced NLP techniques

    Add predictive analytics for claim outcome forecasting

    Integrate with Microsoft Fabric for enterprise-level scaling
