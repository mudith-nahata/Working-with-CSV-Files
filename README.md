# Working-with-CSV-Files
CSV files are the Comma Separated Files. To access data from the CSV file, we require a function read_csv() from Pandas that retrieves data in the form of the data frame.
--->filepath_or_buffer: Location of the csv file. It accepts any string path or URL of the file.
--->sep: It stands for separator, default is ‘, ‘.
--->header: It accepts int, a list of int, row numbers to use as the column names, and the start of the data. If no names are passed, i.e., header=None, then, it will display the first column as 0, the second as 1, and so on.
--->usecols: Retrieves only selected columns from the CSV file.
--->nrows: Number of rows to be displayed from the dataset.
--->index_col: If None, there are no index numbers displayed along with records.  
--->skiprows: Skips passed rows in the new data frame.
