# pandas-challenge-1

This program takes client data for a comapny and analyzes that data to return useful information about the client base.

The first part of the program reads the data in and manipulates the already existing data to find basic information about the clients, as well as the top 5 clients who do business with the company most often.

The second part of the program transforms the data to determine how much money the clients are spending on product and shipping, and how much money the company is making from those transactions.

The final part of the program takes that information and creates a summary dataframe that is human readable.

(Note some final conclusions on the data are included in the comments of the program at the bottom)


## Sources used:

How to round a float:
https://stackoverflow.com/questions/455612/limiting-floats-to-two-decimal-points

How to create a mask to filter a pandas data frame:
https://saturncloud.io/blog/how-to-select-rows-from-a-dataframe-based-on-list-values-in-a-column-in-pandas/#:~:text=To%20select%20rows%20from%20a%20DataFrame%20based%20on%20a%20list,to%20select%20the%20desired%20rows.

pandas groupby:
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.groupby.html