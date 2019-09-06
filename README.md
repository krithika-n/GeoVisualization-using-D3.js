# MapVisualization

The choropleth on the left depicts the number of votes cast in the 2016 presidential election. On hovering over the states, a bar chart is generated on the right for the county-wise breakdown and disappears on mouseout.

On checking the checkbox, the choropleth and the generated bar charts use the population normalised (per capita) values ie., #votes=20 and population=100, value used = 20/100=0.2

The grey state(Minnesota) on the choropleth depicts missing values and hovering over some of the states generates an empty bar chart when there is no county-wise data available for those states.

On checking the bonus 1 check box, a heat map is generated in place of the choropleth and has the same functionalities as mentioned above for choropleth i.e., the heat map is generated again with per_capita values instead of raw values. Since the colours of the heat map are determined according to the percentile, the colours do not differ like they do for the choropleth.
