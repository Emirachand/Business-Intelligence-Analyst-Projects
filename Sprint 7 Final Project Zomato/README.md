# Final Project: Zomato Customer Analysis

This was my final project for the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned throughout the TripleTen Program.

The entire project on Tableau can be found [here](https://public.tableau.com/app/profile/emira.chand/viz/ZomatoCustomerAnalysis_17210978374100/Story1?publish=yes).

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Zomato Customer Analysis.docx] | A .docx file with the written report for this project. |
| 2 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 3 | [Requirements.txt] | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 4 | [Zomato Project](https://public.tableau.com/app/profile/emira.chand/viz/ZomatoCustomerAnalysis_17210978374100/Story1?publish=yes) | Entire Project on Tableau |

| Section Title | Description |
| ----------- |----------- |
| DATA | Describes the source of data, included files, tables, and fields. |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions given by TripleTen and those made based on the data and task. |
| Process | A general outline of how this project formed from start to finish. |
| Findings | Insights learned from the data analysis. |

### Data
TripleTen provided an archived file of five separate Excel files from the mock company Zomato. I used three for this project.
- `'Zomato data.zip'`: Compressed Excel files provided by team lead
    - `'orders'`: All orders made from the menu by all customers at all restaurants between Oct. 4th, 2017 and June 26th, 2020.
    - `'users'`: All customers who completed orders during the designated time frame and their demographic information.
    - `'restaurants'`: All restaurants that have received orders on the Zomato app with their cuisines, customer rating, and order information.

### Description:
- This was a Customer Segmentation Analysis.
- 11 charts, 6 dashboards, and 1 story on Tableau.
- Includes charts on different customer segments and dashboards to look up specific information on different customer segments.
- The purpose was to successfully complete the Zomato onboarding project to showcase analytical skills to the mock company.

### Assumptions:
- The provided test datasets are accurate, complete, and consistent.
- Missing values or inconsistencies are minimal and will not significantly impact the analysis.
- The column descriptions accurately reflect the content of each table.
- The provided tables (orders, users, and restaurants) contain all the necessary information for the chosen analysis.
- Zomato's business context and industry trends are considered while interpreting the data.

### Process:
I first learned of the problem presented in its entirety and its requirements for approval. Then, I chose software and created my first submission, the "Decomposition Plan". Afterward, I analyzed the data, created visualizations and dashboards, and wrote the analysis for submission and approval on the first submission.

### Findings:
1. Most popular age range is 21-24-year-olds.
2. Majority of users are men.
3. Most users are unmarried and have no income due to the occupation being students.
4. Weekdays are the most popular times to order.
5. Reviews and ratings for restaurants have no impact on orders placed.

### Summary of Findings

1. **Customer Segments:**
   The majority of Zomato's users are aged 21-24, primarily college students with no income, followed by young professionals aged 25-29. Most users are single and live in small households.

2. **Spending Habits:**
   Users tend to order more on weekdays, with Friday being the peak day for spending, and show a significant drop in spending on weekends. North Indian cuisine is the most popular among users, indicating a preference for familiar local food.

3. **Influence of Ratings:**
   The number of restaurant ratings does not heavily influence ordering decisions, with many orders placed at restaurants with fewer ratings. Users prioritize cuisine preference over restaurant ratings.

4. The analysis of customer data from 2017 to 2020 indicates significant trends in user engagement across different age groups. The 21-24 age group consistently had the highest number of users, peaking in 2018, but experienced a notable decline in the following years. Similarly, the 25-29 age group saw substantial growth in 2018 before a steady decrease. The 30-33 and 18-20 age groups had consistently lower user counts, with a general downward trend from 2019 to 2020 across all age groups. This suggests a possible decline in overall user engagement or external factors affecting customer retention during the later years.

5. The analysis demonstrates a positive correlation between these two metrics: cuisines with higher user counts generally also have higher sales amounts. North Indian cuisine, for example, shows the highest popularity and sales, while other cuisines like desserts and Italian have lower popularity and sales.

6. The analysis depicts the sales amounts for various restaurants, with Domino's Pizza leading the pack with a significant margin. Domino's Pizza stands out with sales amounting to $5 million, which is over $1 million more than the second-highest restaurant, KFC. This substantial lead highlights Domino's strong market presence and popularity. Other notable competitors include Burger King, McDonald's, and Baskin Robbins, each showing respectable sales figures but still trailing behind Domino's by a considerable amount.



### Recommendations for Zomato

1. **Engage Younger Users:**
   Focus on attracting and retaining younger users, especially students and recent graduates. Track user account creation dates to understand user activity durations and develop tailored retention strategies.

2. **Promotional Strategies:**
   Implement lunch hour promotions to encourage weekday orders from young professionals. Offer weekend promotions targeting the 21-24 and 25-29 age segments to boost weekend sales.

3. **Personalized Notifications:**
   Utilize app notifications to drive orders during off-peak times and provide personalized restaurant suggestions based on user preferences. Promote restaurants offering popular cuisines, particularly North Indian, to align with user tastes and increase satisfaction.

4. **Re-engage Declining User Groups:**
   To address the decline in user engagement, particularly among the largest user groups (21-24 and 25-29), Zomato should consider targeted marketing campaigns to re-engage these users and investigate potential external factors that may have contributed to the drop. Additionally, efforts should be made to attract and retain users in the 30-33 and 18-20 age groups by offering age-specific promotions and enhancing user experience based on the preferences and behaviors of these demographics. Understanding and mitigating the reasons for the decline from 2019 to 2020 will be crucial in maintaining a robust and growing customer base.

5. **Broaden Factors Influencing Sales:**
   Given the lack of strong correlation between ratings and sales, Zomato should consider additional factors that may influence restaurant sales, such as location, pricing, marketing efforts, and customer loyalty programs. Focusing on these areas may provide more actionable insights to boost sales. Additionally, Zomato could explore targeted strategies to improve the visibility and appeal of restaurants with higher ratings but lower sales, potentially leveraging customer reviews and social media marketing to attract more patrons. Understanding the diverse elements affecting restaurant performance will be crucial for creating effective growth strategies.

6. **Leverage Cuisine Popularity:**
   Zomato should leverage the positive correlation between cuisine popularity and total sales by focusing marketing and promotional efforts on the most popular cuisines to maximize revenue. Special promotions, discounts, and partnerships with restaurants offering North Indian, Chinese, and other popular cuisines can further boost sales. Additionally, to diversify and increase overall sales, Zomato should explore strategies to enhance the appeal of less popular cuisines, such as offering combo deals, featuring these cuisines in marketing campaigns, and encouraging user reviews to attract more customers. By balancing efforts between popular and less popular cuisines, Zomato can optimize growth and customer satisfaction.

7. **Adopt Successful Competitor Strategies:**
   The data suggests that Domino's Pizza has a robust market strategy and customer base that allows it to outperform its competitors. For other restaurants to compete effectively, they may need to investigate the strategies that Domino's employs, such as its marketing techniques, menu offerings, customer engagement practices, and delivery services. Recommendations for other restaurants to enhance their sales include:
   - **Enhancing Delivery Services:** Like Domino's, offering efficient and widespread delivery options can significantly boost sales.
   - **Marketing and Promotions:** Increasing marketing efforts and running promotions can attract more customers.
   - **Menu Diversification:** Expanding and diversifying the menu to cater to a broader audience can help attract more customers.
   - **Customer Engagement:** Implementing loyalty programs and engaging with customers through social media and other platforms can enhance customer retention and attract new customers.

   By adopting some of these strategies, other restaurants might be able to narrow the gap and increase their sales figures.

