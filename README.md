Tasks that i did during Week 1 ---->


I Started off by importing Pandas and NumPy — my go-to libraries for handling tabular and numerical data.
After that, I loaded an Excel file named "climate_change_download_0.xls" and focused on the "Data" sheet. At first glance, I used methods like .head(), .columns, and .info() to get a basic idea of the structure, the column names, and the types of data I was dealing with.
While browsing the dataset, I noticed that the actual data didn’t start right from the top — there were a couple of extra header rows. So, I reloaded the file using skiprows=2 to clean that up and align the data properly.

Once the structure looked right, I checked the shape of the dataset and started cleaning. I removed rows where all values were missing, since they didn’t contribute any information.To make things more readable, I renamed "Country name" to just "Country", which felt cleaner and easier to work with.
Next, I took a closer look at the list of columns and kept only the ones that were actually useful for the kind of analysis I wanted to do.

I also checked for duplicates and removed any I found, just to make sure there was no redundancy in the data.
To wrap up the cleaning, I used .isna().sum() to scan for missing values and make sure the dataset was in good shape. I double-checked that all column names were consistent and didn’t contain hidden issues like spacing or duplicates.

Finally, I saved the cleaned version into a new Excel file called "cleaned_climate_data.xlsx" — ready to use for analysis or visualization.


Tasks that i did during Week 2 ---->


I began by setting up my environment with the libraries I knew I’d need — NumPy and Pandas for working with the data, and Seaborn and Matplotlib for visualizations. I also brought in a stats function for checking multicollinearity later.

Next, I loaded a dataset named data_cleaned.csv. After loading it, I quickly checked the shape of the dataset to get a sense of how big it was. Then I looked at the data types of each column, which helped me understand what kind of operations I could perform on them.

To get an initial feel for the data, I used .head() to peek at the first few rows, and .describe() to look at some basic statistics — like the mean, standard deviation, and range — for each numerical column.

Curious about how carbon emissions have changed over time, I grouped the data by year and calculated the average CO₂ emissions per capita for each year. Then I visualized this trend using a line plot, which gave a clear picture of how the global average has shifted.

I didn’t stop there — I also wanted to explore the connection between total CO₂ emissions and population size. So, I created another line plot comparing those two variables. It was interesting to see how population growth might be influencing total emissions.

All in all, this initial exploration helped me build a basic understanding of the dataset and guided me toward what I might want to analyze next.
