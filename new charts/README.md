

📘 Scatter Plots with Matplotlib — Guided Lab 386.6.1
📌 Lab Overview
This lab introduces the fundamentals of creating scatter plots using Matplotlib and NumPy. You will learn how to visualize relationships between variables, customize marker size, color, transparency, and apply colormaps. The lab also includes real‑world data visualization using a housing dataset.

By the end of this lab, you will be able to create, customize, and interpret scatter plots effectively.

🎯 Learning Objectives
Understand how scatter plots represent relationships between variables

Use plt.scatter() to create scatter plots

Customize marker size, color, shape, transparency, and colormap

Visualize real‑world datasets using scatter plots

Interpret multi‑dimensional data using color and size encoding

🧰 Technologies Used
Python 3

NumPy

Matplotlib

Pandas (for real‑world dataset)

📦 Installation
Before running the lab, install the required libraries:

bash
pip install numpy matplotlib pandas
📚 Scatter Plot Syntax
python
plt.scatter(x, y, color="", s= , c= , cmap="", alpha= )
Key Parameters
Parameter	Description
x, y	Arrays of equal length representing coordinates
s	Marker size
c	Marker color
marker	Marker shape
cmap	Colormap for mapping values to colors
alpha	Transparency (0 = invisible, 1 = solid)


🧪 Lab Examples
Example 1 — Simple Scatter Plot
Demonstrates a basic scatter plot with fixed marker size and color.

Example 2 — Variable Marker Sizes
Shows how marker size can represent an additional dimension of data.

Example 3 — Transparency (Alpha)
Uses alpha to make overlapping points easier to see.

Example 4 — Combining Color, Size & Transparency
Applies a colormap and random sizes to visualize multi‑dimensional data.

Example 5 — Comparing Two Age Groups
Plots two age groups (20–39 and 40–69) with different colors and transparency.

Example 6 — Random Data Visualization
Uses NumPy’s random generator to create a colorful, size‑varying scatter plot.

Example 7 — Real‑World Housing Data
Visualizes California housing data using:

Longitude & latitude (location)

Population (marker size)

Median house value (marker color)

This example demonstrates how scatter plots can reveal geographic and economic patterns.

📁 Submission Instructions
Submit your completed lab using the Start Assignment button in Canvas.

You may submit either:

✔ Jupyter Notebook
your_name_scatterplots.ipynb  
Include:

All code examples

Output visualizations

Comments explaining each section

✔ Python Script
your_name_scatterplots.py  
Include:

All examples in order

Comments for clarity

🙌 Author
Manuel  
Guided Lab — 386.6.1
Matplotlib Scatter Plots