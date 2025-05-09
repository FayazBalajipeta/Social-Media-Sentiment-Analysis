Imports necessary libraries: pandas for data manipulation and matplotlib.pyplot for plotting.
Loads data: Reads a CSV file named 'sentimentdataset.csv' into a pandas DataFrame called df.
Cleans sentiment data: Converts the 'Sentiment' column to lowercase and removes leading/trailing whitespace.
Prints column names: Displays the names of all columns in the DataFrame for inspection.
Defines a hashtag counting function: Creates a function called count_hashtags to count the occurrences of specific hashtags within a string.
Applies hashtag counting: Uses the count_hashtags function to create a new column called 'Hashtag' in the DataFrame, storing the count of target hashtags found in the 'Sentiment' column.
Filters data: Selects rows (users) who have at least one target hashtag in the 'Hashtag' column, storing them in a new DataFrame called users_with_hashtags.
Counts hashtag usage: Calculates the number of users who used each of the target hashtags and stores these counts in a dictionary called hashtag_counts.
Prints hashtag counts: Displays the counts of each target hashtag along with the number of users who used them.
