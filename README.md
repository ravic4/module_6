# module_6: San Francisco Housing
## Housing Rental Analysis:
### Brief: 
#### Using three CSV's we analyze San Francisco housing history to understand and draw conclusions from price per square foot, to gross rent between 2010-2016. We use a mix of line, bar, and map plots to communicate our findings. 

### How the code works: 
#### Imports: Pandas, hvplot, pathlib, bokeh. Though Shah also: Geoviews, Xarray, Cartopy.
#### Reads the data from the resource folder: sfo_neighborhoods_census. 
#### Checks that the data has been read for first and last 5 rows. 
#### By using the 'groupby' function by year and average of: housing_units we organize housing units between 2010 to 2016. 
#### We then use the hvplot.bar to plot the code accordingly and style the graph up. 
#### Study 1: We organize by sale price per sqfoot and gross rent, and rename the columns for formality. We then plot the graph and make it have buttons using: groupby "neighborhood" function
#### Study 2: For the interactivce map we use index_col: "Neighborhoods" to match the longitude and latitude with SF neighborhoods. 
#### we concat the dataframe to to include sale price per sqr foot, housing units, and gross rent. 
#### lastly, we plot using hvplot.points to plot the locations around San Francisco 



### Worked with Kayla on this. Also received help from Tutor Fauwaaz, and supported a classmate: Aditya for this as well for the Bar Chart question. 
#### Sources 
##### https://stackoverflow.com/questions/72863835/how-to-create-column-names-in-pandas-dataframe 
##### https://pandas.pydata.org/pandas-docs/version/1.0.1/reference/api/pandas.to_datetime.html 
##### https://www.freecodecamp.org/news/dataframe-drop-column-in-pandas-how-to-remove-columns-from-dataframes/#:~:text=drop()%20Method%20in%20Pandas,the%20inplace%20parameter%20to%20True%20.
##### https://stackoverflow.com/questions/11346283/renaming-column-names-in-pandas 