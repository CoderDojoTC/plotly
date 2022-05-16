# A Simple Bar Chart

## Plotly Express

Plotly Express is a small subset of the extensive Plotly libraries that are idea for beginners.

We will begin all our examples with this line:

```py
import plotly.express as px
```

This line will load the ploty express library and rename it as "px".


We will end with the following:

```py
fig.show()
```

This will take our data and render it to the screen.


```py
import plotly.express as px
data_canada = px.data.gapminder().query("country == 'Canada'")
fig = px.bar(data_canada, x='year', y='pop')
fig.show()
```

This will open a web browser and display the following plot:

![Plot of Canada Population Over Time](../img/plot-canada-population.png)

Other than the first and last lines, the plotting program just needs two lines.

```py
data_canada = px.data.gapminder().query("country == 'Canada'")
```

This gets some sample data from a dataset called "Gap Minder" and runs a query for the country of Canada.


## Exercises

On line 2, try to change the "country" variable to be another country such as "india" or "ireland".

On line 3 change X-Axis label to be "Time" and Y-Axis label to be "Population".