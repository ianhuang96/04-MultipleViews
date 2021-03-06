Assignment 4 - Visualizations and Multiple Views  
---
Data: https://www.kaggle.com/zusmani/us-mass-shootings-last-50-years  
Link: https://ianhuang96.github.io/04-MultipleViews/

---

I get US mass shooting dataset from kaggle and visualized it by multiple views.

- US map represents the shooting in all states. 
- Bubble chart represents the cause of shootings.
- Bar chart represents shootings every year from 1983 to 2017.

When you click a state on map, bubble chart will show the cause of shootings in that state and Bar chart show how many shootings happened in that year. If you click a bubble which represent a type of cause, the map will show all the shootings by that cause over the country and bar chart shows that kind of shooting each year. If you click a year in bar chart, the map will show how many shootings happend in each state in that year and bubble chart will show all the cause in that year.

![image](image/view.gif)

# Technical achievement

- In bubble chart, text size changes according to bubble size.
- When mouse over chart, the label will show the amount.
- Rotated x-axis label.
- Used map in order to visualize the amount of shootings in each state.
- Used bubble chart to visualize the amount of shootings by different causes.
- Used bar chart visualize the amount of shootings in every year.

# Design achievement

- In map chart, the more shootings, the deeper red of color in state is.
- In bubble chart, I use category10 in order to distinguish differen causes.
- Used red color to represent shooting in both of map and bar chart.

# Reference

https://gist.github.com/NPashaP/a74faf20b492ad377312                
https://bl.ocks.org/mbostock/4063269
