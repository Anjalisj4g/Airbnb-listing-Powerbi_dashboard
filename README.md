# Airbnb-listing-Powerbi_dashboard

In this project, I have done the data analysis on the availability of airbnb in the New York city. The dataset consisted of 16 columns and 48896 rows. The dataset contained airbnb name, id, host id, host name, location, neighbourhood, availability, price etc. I have created report on the basis of room type, number of reviews, night counts, price, neighbourhood etc. 
Here are the processes that I have done to complete the project.
# Importing and Preprocessing Dataset.
I have imported the csv file of airbnb listing from Get data option. 

# Effective preprocessing techniques applied to ensure data quality.
I have removed cells containing errors and empty values from columns id, host id, host name etc.
I have changed datatype of column Last review. This column contains date of last review. Then I extracted year from the from this column and added it on a new column 'Year'.
I have created a column named 'Price division' that grouped airbnb based on price ranges of '0-1000','1000-4000' and 'More than 4000'.
I have created another column 'Night counts' that grouped airbnb based on night counts that ranges from '0-30', '31-100' and 'Above 100'.
Another column named 'Review count' was created that grouped airbnb based on number of reviews that ranges from '1-100', '100-500' and 'more than 500'.

# Visuals
I have used visuals like column chart, donut chart, pie chart, cards, slider, line chart, table etc to analyse data.

# Some of the insights derived from the analysis are given below :

* Number of Hosts : 39000
* Price range below $1000 - 38547
* 100m- 500 reviews - 5020 airbnb
* Most airbnb are Retire rooms or apt.
* Price range of most of the airbnb lies between $ 0-1000.
* Airbnb with most number of reviews and room type is Retire room or apt.
* Retire rooms are comparatively expensive.
* Manhattan is the neighbourhood group o most number of airbnb.
* Most of the airbnb have night counts ranging from 0-30.
* Most of the airbnb are reviewed 0-100 times.
* Most of the airbnb are last reviewed in 2019.

  
# Inclusion of Buttons, Bookmarks, Images
* Right button is inserted to view the page containing table.
* Left button is used to move back to the first page.
* Bookmark button is inserted to see the latest trend of airbnb availability, that is, airbnb listing of 2019.
* Images are added to attract and complement the data analysis.

  
