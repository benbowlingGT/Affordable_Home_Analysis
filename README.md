# Home_analysis

##Background

This project seeks to better understand what affects the affordability of homes in states of the US that interest us as a group.

##Before You Begin

Create a new repository for this project in github.

Clone the new repository to your computer.

Inside the folder you just created, add new files called 'resources' and 'analysis'

Push the above changes to GitHub.

Cleaning the data
Clean the data accordingly by removing the necessary outliers, NAN and, other unavailable data.

Part 1: BASED ON THIS DATA, WHICH ATTRIBUTE (NUMBER OF BEDROOMS/BATHS, SQUARE FOOTAGE) MOST AFFECTS THE SELLING PRICE OF A HOME?
The first requirement is to create 3 regression analysis using correlatio to showcase the following relationships:

Sale price vs. house size
Sale price vs. Bedrooms
Sale price vs. Bathrooms
Part 2: What is the average sales price for each state and how does the number of rooms compare to the sales price for that state?
Grouped the data by the states and territories and called it group_by_states

Used the .mean() function on the bedrooms, bathrooms, and price columns

Created a bar graph to show the average sale price for each state and sorted the states from highest to lowest

Created a bar graph to show the average number of bedrooms and bathrooms for each state

Created a scatter plot to show how the average number of rooms relate to the sales price for each state with blue circles being bedrooms and orange triangles being bathrooms

Part 3: Which state has the most affordable 3 bedroom 2 bath home?
Identify all of the 3 bed 2 bath homes in every state

Separate homes by state

Sort homes by price (in decreasing order)

Identify home with the least price in each state

Part 4: Average Cost of Home By State
Used the .value_count function to determine the number of homes in each state by counting each time the state showed up in the dataset.

Created a pie chart to show the amount of homes in each state

Created a dataframe to locate all information for the state of Pennsylvania, which had the most number of homes

Created datasets for the price & size of homes in Pennsylvania

Created a scatter plot for the Pennsylvania sale price vs Pennsylvania home square footage.

Calculated the correlation coefficient for the Pennsylvania sale price & Pennsylvania home size.
