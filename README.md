# Blinkit-Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/0eeb696f-74c8-4723-b2d1-442c6fac130c/795acb4ccef1a2ca16fe?experience=power-bi

## Problem Statement

Blinkit, a leading grocery delivery platform, faces challenges in understanding how various product attributes (such as fat content and item type) and outlet characteristics (like location, size, and establishment year) impact total sales performance.

This project aims to explore these relationships using data-driven insights and visual analytics to help the company optimize outlet operations, improve inventory planning, and boost overall sales performance.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Outlate Size".

- Step 5 : Added 4 KPI's using card visuals
     1) Total Sales
     2) Average Sales
     3) Average Rating
     4) Number Of Items

 To show the Average Sales & Average
 Rating we have created Mesures

 * Avg_Rating = AVERAGE('BlinkIT Grocery Data'[Rating])

 * Avg_Sales = AVERAGE('BlinkIT Grocery Data'[Sales])

 Snap of the KPI'S,

![Dashboard_upload](https://raw.githubusercontent.com/rawdyt/Blinkit-Dashboard/main/nwew.jpg)


- Step 6 : We have provided 3 different Visual filters were added  so that we can filter the data as per our need (Outlate type, Outlate location type,Outlate size)
 so that we can decide where to focus.
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the card visual.
- Step 8 : We have added different visual 
 1) Number of items by fat content (Donut chart)
 2) Fat By Outlate (Clustered bar chart)
 3) Item Type (Bar chart)

 For these above visuals we have 
 added     
 horizontal filter pen to filter 
  
  1) Total sales
  2) Average Sales 
  3) Number of items 
  4) Average Rating

- Step 9 : Area chart to show Total sales by outlate establishment year so that we can understan the progress by the years

Step 10 : Table visual to show the 
 1) Total Sales
 2) Number of items
 3) Average Sales
 4) Average Rating

As per the Outlate Type

# Snapshot of Dashboard (Power BI Service)

![Dashboard](https://raw.githubusercontent.com/rawdyt/Blinkit-Dashboard/main/Dashboard.jpg)


# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

1) Low fat items generated the highest total sales, accounting for nearly double that the regular pizza.

2) Medium size outlate have generated High sales.

3) Tier 3 have highest sales.

4) Fruit & Vegitable, Snack Foods, Households these are 3 highest selling item types.

5) Outlates which are established in 2028 are performing better than other.

6) Super Market type1 have the highest sales than other.
