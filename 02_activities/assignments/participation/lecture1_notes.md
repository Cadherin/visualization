# Visualization Module - Lecture 1 Notes | Date of lecture: June , 2026

1. The first coding exercise demonstrated the randomly generating x, y integers and have them plotted on a scatter plot using the matplotlib package.

2. The numpy library was used to generate random numbers. For instance, np.random.randint(0,100,50) was used to generate 50 random integers with values between 0 and 100. 

3. np.arange(50) is used to create a list of values from 0 to 49. Note that the starting value in python is generally 0 and not 1.

4. Related to scatterplot creation:
- fig refers to the canvas of the plot.
- ax refers to the subplot area where the data points are drawn.
- The figure size is defined as (5, 3), 5 here is the width and 3 is the height. 
- ax.scatter(x,y) woudl create a scattre plot using the x and y values

5. Related to bar chart creation:
- Using similar code for generating the scatter plot, the code can be slightly adjusted to generate a bar chart. 
- ax.bar(x,y) would create a bar chart with x and y values

6. Related to line chart
- ax.line(x,y) would create a line chart

7. To create a histogram, we use the below, x values is not required here:
- ax.hist(y)

8. To add axis labels and titles, the following codes can be used:
- ax.set_title('insert title')
- ax.set_ylabel('insert y label)
- ax.set_xlabel('insert x label)
- fig.tight_layout()

9. fig.tight_layout() is applied to the fig object instead of the subplot. It makes the plot look tighter and cleaner.

10. Fonts for plot titles and labels can be customized and applied to the plots. 
- fontdict is a font dictionary that can be used to define the font style, size, color, etc.
- The loc function can also be used to specify how the title or label is aligned with respect to the plot

11. We can also modify how data points are displayed (e.g. color, marker, etc.)

12. If the file is .py, fig.show() would be needed to display the plot. But when running the code in a Jupyter notebook, after the code is run, the plot is automatically displayed.

13. We can also create a line plot and show all data points as markers in a particular style. The line style and width can also be customized. Keywords for these features in the function include: marker, color, linestyle, linewidth, etc. 

14. There exist a gallery that provides code for colors. Instead of describing colors in words, specific codes can be used to specify them. https://matplotlib.org/stable/users/explain/colors/colors.html#colors-def 

15. Other functions that enables customization of markers include: markersize, markeredgecolor, markerfacecolor

16. Grid lines can be created with ax.grid() for both x- and y-axis. Line style and line color can also be customized.