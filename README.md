# Call Center Dashboard

![Overview of Dashboard](https://github.com/joel-the-analyst/Call-Center-Analysis/blob/main/Call%20Center%20Final%20Dashboard.png)

## Overview
This call center dashboard is designed to monitor and evaluate the performance of a call center, providing actionable insights into key metrics such as call volume, agent performance, customer satisfaction, and operational efficiency. 

The dashboard equips managers and stakeholders with a clear view of daily operations, enabling data-driven decisions to enhance customer service quality and improve team performance.

---

## Key Features
The dashboard is divided into several key sections that focus on different aspects of call center operations:

### 1. **Overall Summary**
At the top, the dashboard displays key performance indicators (KPIs) for a high-level overview of the call center’s performance:
- **Total Calls:** The total number of calls handled by the call center (5K in this case).
- **Number of Agents:** The total number of active agents (8).
- **Average Speed of Answer:** The average time (in seconds) it takes for agents to answer calls (68 seconds).
- **Average Talk Duration:** The average length of calls (225 seconds).
- **Rate of Answered Calls:** The percentage of incoming calls answered by agents (81%).
- **Rate of Resolved Calls:** The percentage of calls resolved successfully during the interaction (73%).
- **Average Satisfaction Rate:** The average satisfaction score provided by customers (on a scale of 1–5).

---

### 2. **Call Volume Analysis**
This section provides insights into the volume of calls received:
- **Call Volume by Date:** A line chart visualizing call volume trends over time. The chart indicates seasonal trends or fluctuations in call volumes. For instance, a decline in call volume in Feberary and March may suggest reduced customer issues or improved self-service tools.
- **Calls Made by Each Agent:** A bar chart comparing the number of calls handled by each agent. Agent Jim handled the highest number of calls (666), while Stewart handled the least (592). This could indicate uneven workload distribution among agents.
- **Calls Based on Each Topic:** A breakdown of calls categorized by topics such as "Admin Support," "Payment Related," "Streaming," etc. Streaming and Payment-Related topics received the highest number of calls (1,032 and 1,021, respectively). These areas may require additional resources or proactive customer communication to reduce call volume.

---

### 3. **Agent Performance Analysis**
This segment evaluates individual agent performance:
- **Resolved Rate of Each Agent:** The percentage of calls successfully resolved by each agent. Agents Joe and Stewart have the highest resolution rate (74%), while Becky lags slightly (72%). Training or process reviews could help improve Becky's performance.
- **Average Talk Duration of Each Agent:** A comparison of average call durations for all agents. Dan has the longest average talk duration (281 seconds), while Jim has the shortest (219 seconds). This might indicate differences in how agents handle calls—longer durations could signal thorough assistance or inefficiency.
- **Average Speed of Answer of Each Agent:** The time taken by agents to answer calls, highlighting efficiency. Greg leads in answering calls the fastest (63 seconds), while Martha takes the longest (73 seconds). Adjusting staffing levels during peak times could help improve average answering times.

---

### 4. **Call Handling Efficiency Analysis**
Focused on operational efficiency, this section includes:
- **Average Speed of Answer by Date:** A line chart showing trends in answering speed over time. The average speed of answering calls has improved slightly from January (67 seconds) to March (68 seconds), suggesting progress but still room for optimization.
- **Resolution Rate by Average Talk Duration:** A bar chart examining the relationship between talk duration and resolution rates. Resolution rates peak at moderate talk durations (~250–300 seconds), indicating that concise yet thorough conversations are most effective.
- **Rate of Unanswered Calls by Time Interval:** A chart showing when the most calls go unanswered, segmented by time intervals. The highest rate of unanswered calls occurs between 6 AM and 6 PM (19%). This indicates a need for increased staffing or improved self-service options during this period.

---

### 5. **Topic-Based Analysis**
This section assesses the performance of calls based on specific topics:
- **Average Satisfaction Rate of Each Topic:** A bar chart displaying customer satisfaction rates for different call topics. Topics such as Admin Support and Payment Issues have a slightly lower satisfaction rate (3 out of 5). This could highlight areas where agents or processes need improvement.
- **Resolution Rate of Each Topic:** The percentage of calls resolved for each topic category. Resolution rates for topics like Streaming and Contract Issues are above average at 74%, indicating relatively strong performance in these areas. Continued focus on these topics can maintain or further improve the resolution efficiency.

---

## Insights Gained
From this dashboard, several key insights can be derived:
- **Agent-Specific Recommendations**: Agents with lower resolution rates or slower answering times (e.g., Martha, Becky) could benefit from targeted coaching.
- **Operational Adjustments:** The lowest unanswered call rate occurs during the evening hours (6 PM to Midnight at 14%), indicating sufficient staffing during this period. However, the unanswered call rate is higher during the morning and afternoon (19% each), suggesting that additional staff or optimized workflows might be needed during these times to improve customer satisfaction.
- **Process Improvements:** Topics such as Streaming and Payment-Related have slightly lower resolution rates (around 72%) compared to others like Admin Support (74%). Proactively addressing common challenges in these areas through targeted training or improved support workflows could help boost resolution rates and overall efficiency.
- **Customer Experience Focus**: Enhancing satisfaction rates for specific topics through improved support workflows and tools could lead to better customer retention.

---

## Technical Details
- **Tool Used:** Power BI
- **Data Sources:** The dashboard was created using sample call center data, which includes metrics such as call timestamps, agent details, call topics, and customer feedback.
- **Filters:** Interactive slicers allow users to filter the data by:
  - **Topic:** Admin Support, Payment Related, Streaming, Technical Support, etc.
  - **Agent:** Specific agents such as Becky, Dan, Diane, etc.
  - **Time Interval:** Morning (6 AM–Noon), Afternoon (Noon–6 PM), and Evening (6 PM–Midnight).

---

## How to Use
1. **Clone the Repository:** Download the repository to access the Power BI file.
2. **Open the Dashboard:** Use Power BI Desktop to open the `.pbix` file and explore the dashboard.
3. **Customize Filters:** Use the slicers to filter data by topic, agent, or time interval to analyze specific trends.

---

## Future Enhancements
In upcoming iterations, the following features can be added to improve the dashboard:
- **Predictive Analytics:** Forecasting call volumes and agent workload based on historical data.
- **Drill-Down Capabilities:** More granular views for individual agent performance or specific time intervals.
- **Real-Time Data Integration:** Connecting the dashboard to live data sources for real-time monitoring.

---

## Conclusion
This Call Center Dashboard is a powerful tool for monitoring and optimizing call center operations. By providing detailed insights into key metrics, it empowers stakeholders to make informed decisions that improve efficiency and customer satisfaction.

Feel free to explore the repository and provide feedback. Collaboration and suggestions are always welcome!
