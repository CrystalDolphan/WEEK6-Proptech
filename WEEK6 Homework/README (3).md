# Proptech
Proptech is a tool that analyzes and visualizes real-estate data in order to help investors choose the best property to invest in. In this specific file, we analyze the housing data of San Franciso and display four graphical, interactive demonstrations.

## Trend on Housing Units Per Year

Firstly, we import the data and classify them by year using the groupby function. Then we are able to plot a **bar chart** showing the number of housing units in San Francisco every year, which is an overall increasing trend. 
![](./images/6-4-zoomed-housing-units-by-year.png)



## Sale Price Per Square Foot and Average Gross Rent

Secondly, we group the data by neighbourhood, calculate the average result and compare the growth trends of sales price per square foot and gross rent through constructing two **line plots** on the same graph. The result shows a much steeper line for the growth of gross rent than that for the sale price.
![](./images/6-4-avg-sale-px-sq-foot-gross-rent.png)
![](./images/6-4-pricing-info-by-neighborhood.png)

## Interactive Neighbourhood Map

Thirdly, we plot an interactive **Open Street Map** to further visualize the data of rental income and sales prices of the neighbourhoods in San Francisco. 
![](./images/6-4-geoviews-plot.png)

## Conclusion
 As a result, we are able to reach the conclusion that the trend in rental income growth is increasing much faster than that of the sales prices and holds true for all the neighbourhoods across San Francisco. Hence, the **one-click, buy-and-rent** strategy is very plausible. 
Additionally, I would suggest investing in neighborhoods located in the southern suburb of San Franciscon since they have the highest rental income.
