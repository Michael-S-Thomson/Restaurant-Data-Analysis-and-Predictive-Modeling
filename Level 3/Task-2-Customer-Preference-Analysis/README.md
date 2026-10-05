# Level 3 - Task 2: Customer Preference Analysis

## Objective

Analyze customer preferences by examining the relationship between cuisines,
restaurant ratings, and customer votes.

## Analysis Performed

### 1. Cuisine and Ratings

Restaurants with multiple cuisines were split into individual cuisine entries.
The average Aggregate Rating was then calculated for each cuisine.

To make the comparison more reliable, cuisines with fewer than 20 restaurants
were excluded from the filtered rating analysis.

### 2. Highest-Rated Cuisines

Some of the highest-rated cuisines in the filtered analysis include:

- International
- Southern
- Vegetarian
- Sandwich
- Grill
- Steak
- Sushi
- Goan
- Breakfast
- Mediterranean

International cuisine had the highest average rating among cuisines meeting
the minimum restaurant-count requirement.

### 3. Popular Cuisines Based on Votes

Total votes were analyzed to identify cuisines receiving the most customer
engagement.

The cuisines with high total votes included:

- North Indian
- Chinese
- Italian
- Continental
- Fast Food

North Indian had the highest total number of votes.

## Important Observation

Total votes are influenced by the number of restaurants offering a cuisine.
Therefore, total votes and average rating measure different aspects of
customer preference.

- **Total votes** indicate customer engagement/popularity.
- **Average rating** indicates customer satisfaction.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Conclusion

The analysis shows that customer preferences vary across cuisines. Some
cuisines receive high average ratings, while others receive a larger number
of customer votes. Analyzing both rating and vote count provides a more
complete understanding of customer preferences.
