---
title: '"Udacity-Data-Analyst-Advanced-Data-Story-Telling"'
categories:
tags:
---

<!-- more -->
# Introduction to Data Visualization
## Plots
### Univariate
#### Quantitive Data (Continuous, Discrete)
- Histogram (*)
- Box-and-Whisker Plot
- Stem-and-Leaf Plot
- Normal Quantile Plot

#### Categorical Data (Ordinal, Non-ordinal)
- Bar Chart (*)
- Pie Cart
- Pareto Chart

### Double Variables
#### Quantitive Data
- Scatter Plot
        - r: Correlation Coefficient
        - Strength: weak |r|<0.3 / moderate 0.3<=|r|<0.7 / strong |r|>=0.7
        - Direction: positive/negative
- Line Plot
Line plots are a common plot for viewing data over time. These plots allow us to quickly identify overall trends, seasonal occurrences, peaks, and valleys in the data.
#### Categorical Data
- Side-by-side Bar Chart

### Multi-Variables
#### 3: Sale/Date/Product
- line chart
- stack line chart
- stack bar chart

#### 3+
- Data Dashboard


# Design
## Rules
- Understand the context - this means knowing your audience and conveying a clear message about what you want your audience to know or do with the information you are providing.
- Choose an appropriate visual display - this was covered in the last lesson. Check out the recap page here if you need a quick refresher.
- Eliminate clutter - you should only provide information to the user that helps convey your message.
- Focus attention where you want it - build visualizations that pull attention to the message you want to highlight.
- Think like a designer - you will learn a number of design principles in this lesson to assist as you start to put together your own data visualizations.
- Tell a story - your visualizations should give the audience a story. The most powerful data visualizations move people to take action.

## Purpose
### Reasons for creating visuals using data
- Exploratory Analysis: is done when you are searching for insights. These visualizations don't need to be perfect. You are using plots to find insights, but they don't need to be aesthetically appealing. You are the consumer, and you need to be able to find the answer to your question from these plots.
- Explanatory Analysis: is done when you are providing your results for others. These visualizations need to provide you the emphasis you need to convey your message. They should be accurate, insightful, and visually appealing.

### Steps of the data analysis process
- Extract - Obtain the data from a spreadsheet, SQL, the web, etc.
- Clean - Here we could use exploratory visuals.
- Explore - Here we use exploratory visuals.
- Analyze - Here we might use either exploratory or explanatory visuals.
- Share - Here is where explanatory visuals live.

##  Visual Encodings
In general, color and shape are best for categorical variables, while the size of marker can assist in adding additional quantitative data, as we demonstrated here.
- Color
- Shape
- Size

# Data Visualizations in Tableau
## Connecting to Data
In this section, you will get started with importing data into Tableau. Tableau public has fewer options, but paid versions of Tableau are quite extensive connecting directly to databases and cloud based data storage systems.

## Combining Data
In this section, you will learn how to connect data from multiple sources for use in your visuals. If you are comfortable with SQL joins, this section should be second nature.
- Union
- Joins

## Worksheets
The visuals you create will be stored in worksheets. This is the template we will be working in for this course.
- Worksheets
- Dashboards
- Stories

## Aggregations
Tableau performs aggregations of our data by default. In this section, you will learn more about how to work with different aggregations, as well as how to break your aggregations into a more granular level of the data.
- Dimentions - axises
- Measures - aggrigations

- columns
- rows
- marks & filters

## Hierarchies
Hierarchies allow you to 'drill' into your data and questions at different levels. One of the easiest ways to think of hierarchies is in relation to time. You could look at your data at a year, month, day, hour, or another level. Moving across these levels is considered working with hierarchies.
- date: year - quarter - month
- self-defining

You can also perform hierarchical calculations in other ways. Imagine you have different companies, with different departments, and teams within those departments. This creates a hierarchy that you might want to analyze at different levels.

## Marks & Filters
Filtering is one of the most powerful techniques in creating dashboards. This relates to the marks portion of a dashboard, which controls the colors, shapes and other attributes of our data. You can think of this like a WHERE statement in SQL used to filter your data to only the parts you are interested in for a specific question.
marks & filters can be used together.

## Show Me
The Show Me portion of Tableau controls what your ending visual looks like. There are a lot of options here. In most cases, Tableau will guess what visual you want to create, but sometimes you might have your own ideas for implementation.
First select variables, then click on the plot you want.

## Small Multiples & Dual Axis
Small multiples & dual charts are a way to visualize data that needs to share an axis for comparison purposes. This and this are great articles for explaining how these two parts of Tableau work and why you might use them.
- Small multiples: 2 or more plots
- Dual Axis: 2 plots in one
## Groups & Sets
Groups and sets are two ways to categorize our data within a visualization. The difference between these two can be confusing, but we will see when and why you would use each.
-  Groups: static
- Sets: dynamic

## Calculated Fields
Often you might add these fields to your dataset before adding your data to Tableau, but sometimes you want to add them to a visualization on the fly. Many of these calculated fields are things you have probably done in a spreadsheet application like finding a total or a cost per item.

## Table Calculations
Table calculations are often used to perform comparisons of our data over time or between groups. A great article on table calculations is available here.
