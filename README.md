## Experiment 17: Basic Charts and Visual Encoding

### Aim
- To visualize data using different types of charts such as Line Chart, Bar Chart, Histogram, and Scatter Plot using Matplotlib and Seaborn.

### Libraries Used
- pandas (pd) → used to create and manage datasets  
- matplotlib.pyplot (plt) → used for creating basic charts and graphs  
- seaborn (sns) → used for advanced and attractive visualizations  
- numpy (np) → used for numerical calculations (mean, etc.)

### Dataset Used
- Columns → Days, Study_Hours, Marks, Attendance, Sleep_Hours, Assignments_Completed  
- Second Dataset → Day, Region, Sales, Profit, Customers, Category  

### Functions and Commands Used
- pd.DataFrame() → create dataset from dictionary  
- print() → display dataset  

- plt.plot() → create line chart (trend visualization)  
- marker='o' / 's' → highlight data points  
- label= → add legend labels  
- plt.legend() → display legend  

- plt.bar() → create bar chart (comparison)  
- bar.get_height() → get value of each bar  
- plt.text() → display values on bars  
- plt.grid() → add grid lines for readability  

- plt.hist() → create histogram (distribution of data)  
- bins= → define number of intervals  
- alpha= → control transparency  
- edgecolor= → set border color  

- np.mean() → calculate mean value  
- plt.axvline() → draw vertical line (mean line in histogram)  

- plt.scatter() → create scatter plot (relationship between variables)  
- list comprehension → assign colors based on condition  

- plt.title() → set graph title  
- plt.xlabel(), plt.ylabel() → label axes  
- plt.show() → display graph  

### Seaborn Functions
- sns.lineplot() → advanced line graph  
- sns.barplot() → advanced bar chart  
- sns.histplot() → histogram with better styling  
- sns.scatterplot() → advanced scatter plot  

### Key Concepts
- Line Chart → shows trends over time  
- Bar Chart → compares values across categories  
- Histogram → shows distribution of data  
- Scatter Plot → shows relationship between two variables  
- Visual Encoding → representing data visually using position, color, and size  

### Conclusion
- The experiment demonstrates that data visualization is an essential tool for understanding patterns and relationships in data. By using charts like line graphs, bar charts, histograms, and scatter plots, complex data becomes easy to interpret. Libraries like Matplotlib and Seaborn provide powerful techniques to present data clearly, making analysis more effective and insightful.  
