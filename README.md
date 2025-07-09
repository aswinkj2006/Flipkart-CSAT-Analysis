# Flipkart CSAT Analysis based on the given Customer Service Data CSV

<https://nbviewer.org/github/aswinkj2006/Flipkart-CSAT-Analysis/blob/main/Flipkart_Project_Aswin.ipynb>

### The given data was analyzed thoroughly using Python with the help of libraries like Matplotlib and Seaborn. 
### The analysis was done mainly on the Agents, Managers, Supervisors and their Tenure Buckets, Shifts, Response Times etc.

## Heres the summary of the analysis.

Based on the analysis of the customer support data, the following key findings have been identified regarding factors influencing CSAT scores:

*   **Overall CSAT Distribution:** The majority of CSAT scores are at the highest level (5), but there is also a significant number of the lowest scores (1), indicating a polarization in customer satisfaction. There is a similar amount of (4) followed by (3) and (2) indicating some unprecedented mixed reviews.

*   **Response Time:** There is a general trend of decreasing CSAT scores with increasing response time, suggesting that faster responses tend to lead to higher customer satisfaction.

*   **Channel of Communication:** Email channel has a lower average CSAT score compared to Outcall and Inbound channels, indicating potential areas for improvement in handling email-based support.

*   **Agent Performance:** There is a clear distinction in CSAT scores between top and bottom performing agents. Addressing the performance of agents with consistently low CSAT scores by giving them the required training is crucial for overall improvement.

*   **Manager Performance:** While most managers have relatively good average CSAT scores, there are variations. Further investigation into the practices of managers with lower average scores could be beneficial.

*   **Agent Tenure Bucket:** The analysis of CSAT ratios by tenure shows that agents in "On Job Training" have the highest ratio of 1-star ratings and the lowest ratio of 5-star ratings. Agents in the "61-90" tenure bucket appear to perform best in terms of minimizing 1-star and maximizing 5-star ratings. Experienced agents (>90 tenure) show a slightly higher ratio of 1-star ratings compared to the 0-90 tenure groups. Supervising the experienced and giving better training to the new ones can significantly improve the CSAT scores.

*   **Agent Shift:** The Morning and Evening shifts have the highest volume of interactions and also a notable number of 1-star CSAT scores. Putting Top Performers in those shifts can improve the CSAT score by a huge amount reducing 1-star scores

*   **Handling Time:** While quick handling times can sometimes result in low CSAT (potentially due to unresolved issues), longer handling times don't necessarily guarantee high CSAT. Quality of resolution seems more impactful than just the duration of the interaction. The analysis of 1-star CSAT scores with short handling times showed that both trainees and experienced agents contribute significantly to this category.

*   **Supervisor Performance (Oliver Nguyen Example):** The detailed look into agents under a specific supervisor (Oliver Nguyen) with a lower average CSAT score highlighted that while some agents under this supervisor perform well, others have significantly low CSAT scores, impacting the team's overall average. This suggests the importance of targeted support and training for underperforming agents, and potentially supervisory coaching.


*   **Addition Research:** From extended analysis of the supervisors of >90 Tenure Bucket and the worse perfoming agents in that category the supervisors and agents who should be trained the most have been marked and once they are taken care of, the overall CSAT scores should see improvement

In conclusion, improving CSAT scores requires a multi-faceted approach focusing on reducing response times, optimizing the email channel, providing targeted training and support to lower-performing agents and those in training, potentially adjusting agent shifts based on performance, emphasizing quality of resolution over speed, and providing effective supervision, especially for experienced agents who may be contributing to low scores with quick handling times.
