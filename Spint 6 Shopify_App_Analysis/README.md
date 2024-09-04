# Shopify Review Landscape of Apps.

This project marks the sixth assignment in the BI Analytics program. Its purpose is to demonstrate the proficiency gained during the Power BI Spring course, 
covering various aspects such as data importing, chart creation, formatting, and utilization of multiple data sources and filters. Moreover, DAX expressions 
are employed for analysis, aimed at uncovering pivotal factors influencing the success of Shopify apps. [Here](https://we.tl/t-I3qpCGUSZ7) 
you can have access the project final upload.



### File Description.

| File | Description |
| ----------- |----------- |
| [README.md]  | This document contains all pertinent information regarding the project, including its objectives, methodologies, and findings. |
| [Requirements.txt] | A text file listing the project's dependencies and requirements as specified by TripleTen. |
| [Shopify App Analysis.pbix](https://we.tl/t-I3qpCGUSZ7) | This is the MS Power BI file containing the presentation, which includes all the sheets.|
| [Superstore.xls] | The raw dataset supplied by TripleTen, utilized extensively throughout the project for analysis and insights generation. |

### Section Description.

| Section Title | Description |
| ----------- |----------- |
| Data Overview | This section provides a comprehensive description of the data utilized in the project, outlining the files and their corresponding information. |
| Analysis Methodology | Offering a broad overview, this section outlines the process undertaken to analyze the data, spanning from initial data ingestion to final insights extraction. |
| Data Insights | Contained within this section are the key insights derived from the analysis of the dataset, shedding light on significant trends, patterns, and discoveries uncovered during the project. |

### Data Overview.
TripleTen provided an excel dataset to be used in tableau to make the analysis, the dataset contains the following sheets and data.

- `'Shopify.xlsx'`: Shopify public data.
  - `'apps'`: Details of the apps on Shopify apps marketplace
  - `'apps_categories'`: Join tables to connect apps with categories
  - `'categories'`: Categories of the apps. Each app has multiple categories
  - `'reviews'`: Each review (row) contains information on user opinion about the related app (rating and comment). Also, it contains the response from the developer if present.

### Analysis Methodology.
For this analysis, I created a sheet for each section. In the first section, focusing on the app landscape, I developed a KPI card to count the unique number of apps, a line chart to track the count of reviews over time, and a scatter plot to analyze the relationship between reviews and average ratings.

In the second part, I used the reviews table to create a new column using DAX, named “helpful_reviews,” based on the “helpful_count” and “rating” columns to determine the average value. I also created another DAX column called “developer_answered” to indicate whether the developer replied (TRUE (1)) or not (FALSE (0)) based on the “developer_reply” column, followed by a scatter plot comparing average ratings to developer responses.

In the final section, I reviewed the apps by establishing a many-to-one relationship between the reviews and apps tables using the “app_id” from the reviews table and the “id” column from the apps table. This allowed me to create bar charts to identify which developers respond most to reviews, assess the usefulness of these responses, and determine the most responsive developers. After completing these visualizations and analyses, I submitted my project.
 
### Data Insights.
1. New Apps are more likely to be rated early in their deployment. Most apps are rated favorably.Stores have received fewer than 5,000 reviews, with a predominant rating around 4 to 4.5. 
2. The developers "Transcy" and "Appstle Inc" are the most responsive.
3. "Pictorem" has the most helpful reviews.
4. Most stores receive favorable reviews.
5. Reviews tend to be higher for apps when the developer responds.
6. The average score for reviews with developer responses is 4.4.
