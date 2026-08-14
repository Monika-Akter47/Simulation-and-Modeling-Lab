Simulation and Modeling Lab- Day3

Customer Wait Time Simulation -- Regular Days vs Busy Days

Simulation and Modeling Lab -- CSE 413 Lab Assignment 3

Problem Statement:

A customer service center wants to understand how long customers wait before being served, under two different scenarios:

Regular days — customers arrive randomly, so wait times follow a uniform distribution between 2 and 12 minutes.
Busy days — wait times follow a normal (Gaussian) distribution with a mean of 8 minutes and a standard deviation of 2 minutes.

This project simulates both scenarios in Python, visualizes the resulting distributions, and compares them using summary statistics.

What the Notebook Does
Part 1 -- Data Generation:
Generates 3,000 wait times from a uniform distribution between 2 and 12 minutes (regular days).
Generates 3,000 wait times from a normal distribution with mean = 8 and standard deviation = 2 (busy days).
Replaces any negative values in the normal distribution with 0, since a wait time cannot be negative.

Part 2 --Visualization:
Plots both distributions as histograms in a single figure using two side-by-side subplots.
Also includes an alternative overlaid histogram (with transparency) showing both distributions on the same axes for direct comparison.

Part 3 --Statistical Analysis:

For both the regular-day and busy-day datasets, computes:

Mean
Median
Standard deviation
Maximum wait time

Requirements:
Python 3
numpy
matplotlib
seaborn

Install dependencies with:

bash
pip install numpy matplotlib seaborn
Running the Notebook
Open SIM_Lab3_Monika_Akter_1047.ipynb in Jupyter Notebook, JupyterLab, or Google Colab.
Run all cells in order.
Histograms will render inline, and the statistical summary will print to the output.
