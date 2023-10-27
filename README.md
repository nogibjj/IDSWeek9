## IDSProject9 Notebook

This notebook explores the Hollywood Movies dataset from the URL: `https://raw.githubusercontent.com/reisanar/datasets/master/HollywoodMovies.csv`.

### Content:
1. **Dataset Import**: Using pandas, the dataset is imported and the first five rows are displayed to get an initial understanding of the data structure.
2. **Filtering Data**: Movies released after the year 2010 are filtered and displayed.
3. **Data Sorting**: The movies are sorted by their profitability in descending order, and the top five are displayed.
4. **Descriptive Analysis**: An average of the RottenTomatoes scores for the movies is calculated.
5. **Data Visualization**: Several scatter plots are generated to explore the relationships between different variables:
    - **Profitability vs. Budget**: Displaying the relationship between a movie's budget and its profitability.
    - **Profitability vs. Year**: Understanding how profitability trends have changed over the years.
    - **Profitability vs. RottenTomatoes Score**: Exploring if critical acclaim (RottenTomatoes Score) has any correlation with profitability.
    - **Profitability vs. Audience Score**: Checking if audience reception has an effect on profitability.
    - **Profitability vs. Opening Weekend Collection**: To see if initial collections have a strong relationship with overall profitability.

### Important Note:
All scatter plots use the variable 'Profitability' on the Y-axis to provide consistency in analysis. However, there seems to be a repetition in titles and axis labels in the plots which might need correction.
