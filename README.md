## Overview

This repository contains the Jupyter Notebook for the Tutor-Marked Assignment (TMA) for my ICT233 Data Programming course. The assignment is focused on data manipulation, analysis, and visualization using pandas, SQLite, and SQLAlchemy in the context of managing tasks and teams.

## Question 1

### 1(a) Loading and Confirming Data

The initial step involves loading tasks and teams data from CSV files, confirming the data, and creating a mapping between the `team` column in `tasks.csv` and the `id` column in `teams.csv`.

### 1(b) Computing Number of Members per Team

Utilizing pandas, a DataFrame is computed to capture the number of members per team using the `groupby()` function.

### 1(c) Visualization of Number of Members per Team

The number of members per team is visualized through a histogram using Matplotlib.

### 1(d) Processing State Transitions

State transitions for tasks are extracted and incorporated into the `tasks_df` DataFrame, which is then saved to a new CSV file (`tasks_df2.csv`).

### 1(e) Computing Commitment and Visualization

Functions are defined to compute commitment and velocity. Additionally, a visualization of commitment and velocity per sprint is created using Matplotlib.

### 1(f) Computing Velocity

A function is implemented to compute the velocity of a team for a given sprint.

### 1(g) Visualization of Commitment and Velocity

A function is defined to calculate and visualize the commitment and velocity of a team across different sprints.

## Question 2

### 2(a) SQLite Database Creation

An SQLite database named `tasks.db` is created, and the tasks data is stored in a table named `tasks`.

### 2(b) Visualizing Story Points by State

A function is implemented to visualize the story points per state for each sprint using Matplotlib.

### 2(c) SQL and ORM Functions

Functions are defined to compute commitment and velocity using both SQLite with SQL statements and SQLAlchemy ORM. Additionally, functions are created to identify users who have the least number of done story points.

## Usage

To run the Jupyter Notebook and execute the code, you may download the file and run it locally on your IDE (eg. Visual Studio Code)


