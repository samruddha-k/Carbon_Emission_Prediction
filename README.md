Tasks that i did during Week 1 ---->

I started by importing pandas and numpy to work with tabular and numerical data.

Then, I loaded the Excel file "climate_change_download_0.xls" and selected the "Data" sheet.

After loading, I used .head(), .columns, and .info() to explore the structure, column names, and data types.

I noticed that the actual data started a few rows later, so I reloaded the file using skiprows=2 to remove the extra header.

I checked the shape of the data and cleaned it by dropping rows where all values were missing.

I renamed the column "Country name" to "Country" to make it more readable and consistent.

I reviewed the column list and kept only the ones that were relevant to my analysis.

I examined the dataset for duplicate entries and removed them if any were found.

I checked for missing values using .isna().sum() to ensure data quality.

I also made sure the column names were unique and clean.

Finally, I saved the cleaned dataset to a new Excel file named "cleaned_climate_data.xlsx" for future use.

