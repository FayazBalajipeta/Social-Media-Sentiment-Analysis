Data Loading and Initial Exploration:

Imports necessary libraries (pandas, NumPy).
Reads the Netflix titles dataset into a pandas DataFrame named df.
Examines the shape, data types, and missing values in the dataset to understand its structure and potential issues.
Univariate Analysis:

Creates histograms to visualize the distributions of 'release_year', 'duration_minutes', and 'date_added_year', providing insights into the frequency and spread of these numerical features.
Generates a bar chart to display the distribution of content types (Movie or TV Show), allowing for a quick comparison of their proportions.
Creates a pie chart showing the percentage distribution of content types, offering another perspective on their relative frequencies.
Bivariate Analysis:

Generates scatter plots to explore relationships between 'release_year', 'duration_minutes', and 'date_added_year', visually revealing potential correlations or patterns between these variables.
Uses box plots to identify potential outliers in these numerical features, helping to understand data variability and identify unusual data points.
Correlation Analysis:

Calculates and visualizes the correlation matrix for numerical features ('release_year', 'duration_minutes', 'date_added_year') using a heatmap, revealing the strength and direction of linear relationships between them.
Prints the correlation matrix and descriptive statistics for numerical features grouped by 'type', allowing for a deeper understanding of how these features vary across different content categories.
Grouped Analysis:

Creates bar charts to compare the average duration and average release year of content based on 'type' (Movie or TV Show), providing insights into differences in these metrics between content categories.
