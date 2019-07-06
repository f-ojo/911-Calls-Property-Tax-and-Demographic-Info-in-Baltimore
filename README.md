# 911-Calls-Property-Tax-and-Demographic-Info-in-Baltimore
This was collobaritive project with Nick Long and Danilo Symonette where we used different data science techniques to find a relationship between 911 Calls, Property Tax, and Demographic Info in Baltimore


A few of these datasets have incorrect calculations in them.

Notebook Folder:
RPT and Census Exploration.ipynb This is an exploration, cleaning, and merging of Real Property Tax and Census Demographics. At least the first time I did, it was the first time I spent with using both

Real Property Tax Exploration is just an exploration and cleaning of Real Property Tax. This was my first notebook

Exploration of Combined Dataset.ipynb The city tax averages are incorrect. I’m not fixing it as we should include our mistakes. 

Neighborhood_TaxAVG_Census CSV Creation.ipynb has the correct city tax averages

Correlations between Tax and Majority Pop.ipynb Shows the correlations between majority population in a neighborhood and it’s average tax price. According to the scatter, there is a correlation between property tax and a majority white population. It’s important to note this is a correlation, not causation. 

Heatmap Creation.ipynb Attempted to use Folium to create the map, it was not very successful

Heatmap Scatter.ipynb Created a scatter of the Long/Lat and added the “heat” of CityTax. Much more successful

911 Police Calls Data Set Cleanup, Merge, and Analysis.ipynb Gives information about the 911 Poice Calls dataset and how we got relevant information from it. Shows how we merge all three datasets together and create a heatmap of that.

CSV Folder:
Shows the datasets we worked with.
