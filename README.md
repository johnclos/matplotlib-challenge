# Matplotlib Homework - The Power of Plots

# Observations and Insights
    # Dependencies and Setup
    # Study data files
    # Read the mouse data and the study results
    # Combine the data into a single dataset
    # Display the data table for preview
    
    # Checking the number of mice.
    
    # Getting the duplicate mice by ID number that shows up for Mouse ID and Timepoint.
    
    # Create a clean DataFrame by dropping the duplicate mouse by its ID
    # Combine the data into a single dataset
    
    # Check the number of mice in the clean DataFrame.
    
# Summary Statistics
    # Generate a summary statistics table of mean, median, variance, standard deviation, and SEM of the tumor volume for each regimen
    # Use groupby and summary statistical methods to calculate the following properties of each drug regimen: 
        # mean, median, variance, standard deviation, and SEM of the tumor volume. 
    # Assemble the resulting series into a single summary dataframe.
    
    # Generate a summary statistics table of mean, median, variance, standard deviation, and SEM of the tumor volume for each regimen
    # Using the aggregation method, produce the same summary statistics in a single line
    
# Bar and Pie Charts
    # Generate a bar plot showing the total number of unique mice tested on each drug regimen using pandas.
    # Use the 'Drug Regimen' group by above to get a count of the unique mice for each drug regimen. 
    # Create the bar plot
    
    # Generate a bar plot showing the total number of unique mice tested on each drug regimen using pyplot.
    
    # Generate a pie plot showing the distribution of female versus male mice using pandas
    # Groupby sex
    # Get the count for each sex
    # Reindex it
    # Create the plot
    
    # Generate a pie plot showing the distribution of female versus male mice using pyplot
    # Create axes which are equal so we have a perfect circle

# Quartiles, Outliers and Boxplots
    # Put treatments into a list for for loop (and later for plot labels)
    # Create empty list to fill with tumor vol data (for plotting)
    # Calculate the IQR and quantitatively determine if there are any potential outliers.
    # Locate the rows which contain mice on each drug and get the tumor volumes
    # add subset
    # Determine outliers using upper and lower bounds
    # Print the outliers for each drug
    
    # Generate a box plot of the final tumor volume of each mouse across four regimens of interest

# Line and Scatter Plots
    # Generate a line plot of tumor volume vs. time point for a mouse treated with Capomulin
    # Create a dataframe for just Capomulin
    # Create a dataframe for just mouse s185
    # Create a line plot
    
    # Generate a scatter plot of average tumor volume vs. mouse weight for the Capomulin regimen
    # Create a groupby dataframe by 'Mouse ID'
    # Create a list for the mean of 'Tumor Volume (mm3)'
    # Create a list for the mean of 'Weight (g)'
    # Create a scatter plot

# Correlation and Regression
    # Calculate the correlation coefficient and linear regression model 
        # for mouse weight and average tumor volume for the Capomulin regimen
    # Create a scatter plot
    # Get the regression data
    # Print the correlation coefficient
    # Create the line for the regression data and plot them
