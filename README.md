# Amazon-Kindle-Data-Analysis
This project focuses on analyzing Amazon Kindle book data using Advanced Excel. 

The analysis helps understand:
* Book distribution across genres and years
* Price categories and rating trends
* Publisher and author performance
* Overall market insights for Kindle books

1. Dataset Description
Key Columns in the Dataset ("data" sheet):
* Book ID – Unique identifier for each book
* Book Title – Title of the Kindle book
* Author – Name of the author
* Publishing Company – Publisher of the book
* Ratings – Average customer rating
* Price – Price of the Kindle book
* Published Date – Book release date
* Genre – Category/genre of the book
* Year – Extracted year from published date
* Price Category – Categorized as Low / Medium / High

2. Data Cleaning Process
Data cleaning was performed directly in MS Excel using the following steps:
Removed inconsistencies, Handled missing values, Date formatting, Created derived columns like Year and Price Category

3. Data Modeling and Data Visualization
The cleaned dataset acts as a single fact table, which was then used to create multiple Pivot Tables.
The dashboard allows quick, visual interpretation of large datasets and supports decision-making.

Pivot Tables Analysis
The workbook contains 6 Pivot Table sheets, each answering a specific business question.

i. Pivot Table 1
Purpose: Analyze number of books by Genre
Chart: Column Chart
Insight: Helps identify dominant genres and content concentration areas in the Kindle marketplace.

ii. Pivot Table 2
Purpose: Average Ratings by Genre
Chart: Column Chart
Insight: Genres with consistently higher ratings indicate better reader engagement and content quality, while lower-rated genres may require improvement.

iii. Pivot Table 3
Purpose:  Top 10 Authors by number of books
Chart: Bar Chart
Insight: Useful for identifying genres that consistently produce quality books rather than just high volume. we can also contact the authors who are not publishing and find out the issue.

iv. Pivot Table 4
Purpose: Average Rating by Publisher
Chart: Column Chart
Insight: Companies with consistently higher ratings indicate better reader engagement and content quality, while lower-rated companies may require improvement.

v. Pivot Table 5
Purpose: Year-wise Book Publication Trend
Chart: Line Chart
Insight: Helps understand growth or decline in Kindle publications over time.

vi. Pivot Table 6
Purpose: Price Category vs Genre 
Chart: Stacked Column Chart
Insight: Helps understand genreChart: Stacked Column Chart-specific pricing behavior and customer affordability patterns.

4. Insights
This project demonstrates how Excel can be effectively used for data analysis and visualization. By cleaning data, modeling it correctly, and using pivot tables and dashboards, meaningful insights about the Kindle book market were derived.

The insights gained are:
* The Kindle marketplace is genre-driven, with uneven content distribution.
* Reader satisfaction is more closely linked to content quality than quantity.
* Medium-priced books dominate, suggesting optimal price acceptance.
* Digital publishing is growing steadily year by year.
* Pricing and quality strategies must be customized per genre.
