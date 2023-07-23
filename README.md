# python-api-challenge

# Description
As part of this module, we have explored if and how weather patterns are impacted as we approach the Earth's equator. 


## Code Source - used in WeatherPY.ipynb
    slope, intercept, r, p, se = linregress(x, y)
 The above code was used to calculate the slope, intercept, r value, p value and standard error for inputted x and y variables. The code was sourced from the below site:
 https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.linregress.html
 
 
    plt.annotate(eq,
                 xy = (x_coord,y_coord),
                 color = "red",
                 fontsize = 13,
                 fontweight = "normal"
                 )

The plt.annotate function was used in the above code to define a function that would create a linear regression for inputted x and y variables. The code was obtained from the following stack overflow forum:
https://stackoverflow.com/questions/68173773/how-to-annotate-maths-equation-in-graph-using-both-latex-and-f-string-formatting

## Code Source - used in VacationPY.ipynb
        hover_cols=['City', 'Hotel Name']

The above code was used to add the hotel name and the country as additional information in the hover message for each city in the map plotted. The code was sourced from the following stack overflow forum:
https://stackoverflow.com/questions/59678780/show-extra-columns-when-hovering-in-a-scatter-plot-with-hvplot 

