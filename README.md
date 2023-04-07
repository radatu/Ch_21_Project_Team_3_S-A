# Ch_21_Project_Team_3_S-A
## Challenge 21 self- and group assessment after Project Team 3's segment-3 project completion and presentation.

<https://github.com/radatu/Ch_21_Project_Team_3_S-A>

# Data Analytics Self-Assessment
## Self-Assessment
Over the course of the project, I played multiple roles, including data collection, cleaning, and modeling. As a team member, my contributions included identifying data sources, cleaning the data, but, primarily, setting up the database. I also collaborated with team members to analyze data and identify insights.

My greatest personal challenge during the project was dealing with missing data. It was challenging to decide how to handle missing data, and we ultimately solved missing population data for various countries and years by finding the dataset author's originnal source (since data we had matched exactly for other countries' yearly data). However, we were able to come up with good solutions to problems that resulted in my ability to have one robust and unified dataset to make up our database.

After the database schema was arrived at, it was uploaded as one database to AWS RDS using postgreSQL where it remained until EOC.

In terms of contributing to roles that I didn't play, I actively tried to coordinate our group members' schedules through Calendly.com to bring the most group members to gether at one time. I participated in team discussions and provided feedback on model selection, mainly, and consideration of our dataset and what was really needed to allow for supervised machine learning. I also reviewed and provided feedback on ETL NaN values and created our group Slack channel, which became our main means of communication. This facilitated efficient and effective communication, right up until presentation time.

## Project and Team Summary
Our project was focused on predicting customer churn for a telecommunications company using machine learning. Our team worked collaboratively by task seperation and specialization of labor on various elements of the project and, later, the presentation. We used our Slack channel as a communication protocol. Because our team was 80% full-time employed, our team depended on Calendly and Slack to coordinate our daily check-ins and make suggestions for each person's swim lanes, to ensure that we stayed on track and coordinated our efforts effectively.

The team coordination wa slargely amatter of individual and independent initiative on the part of each team member. There was an aversion of members to utilizing the AWS RDS and so all members established either, a locally run DB based on the ML_Table.csv, or, as one member suggested, even utilizing the four or five tables that were ultimately joined as the DB for data visualization because the ML_Table was so memory intensive.

One of our team's greatest strengths was our ability to work collaboratively and leverage each other's strengths. We had team members who were experts in different areas, such as ETL, ERD and database creation, EDA, data visualization and modeling, machine learning bringing everything together by having one "gitmaster." We were able to learn from each other and improve our skills. While we recognized the importance of taking breaks and prioritizing self-care to prevent burnout, the close nature. Because our machine-learning modeler worked odd hours, the team contributed least of all to that part of the project, other than providing a good dataset.

We used a logistic regression model to assess CO2 correlation with crop production, and achieved an accuracy of 99% with the ultimate model we chose. Our analysis showed that maize production was the best, most consistent correlate of CO2 production. We also identified that to be the case while distinguishing mmaze production as the highest production sourc e of CO2.

## Conclusion
In future projects, we would prioritize clearer communication protocols for handling missing data and ensure that all team members had a solid appreciation of timimg in our presentation. Had we gone through a dry run, we might have had a better handle on time. It was unfortunate that Nathan's well-constructed, Tableau visuals and Kyla's interactive graphs were a highlight and, as a result of reaching our time limit, which was not clear at the outset though, we missed the opportunity of showing off to the audience the best elements of our presentation.

More importantly, even though, on first appearance, the categorical nature of the data seemed to conduce more to supervised machine learning, it would have been interesting to see what patterns unsupervised machine learning and even deep-learning neural networks might have found as unknown patterns in the data that mere humans might not have discovered without machine learning.

All in all, our team had a good collaborative learning experience working together.

André Rdatus                                                                                                           April 2023