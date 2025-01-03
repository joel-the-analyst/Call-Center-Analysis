# Call Center Dashboard

## Overview
This repository features a comprehensive **Call Center Dashboard** created using **Power BI**. The dashboard is designed to monitor and evaluate the performance of a call center, providing actionable insights into key metrics such as call volume, agent performance, customer satisfaction, and operational efficiency. 

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
- **Call Volume by Date:** A line chart visualizing call volume trends over time.
- **Calls Made by Each Agent:** A bar chart comparing the number of calls handled by each agent.
- **Calls Based on Each Topic:** A breakdown of calls categorized by topics such as "Admin Support," "Payment Related," "Streaming," etc.

---

### 3. **Agent Performance Analysis**
This segment evaluates individual agent performance:
- **Resolved Rate of Each Agent:** The percentage of calls successfully resolved by each agent.
- **Average Talk Duration of Each Agent:** A comparison of average call durations for all agents.
- **Average Speed of Answer of Each Agent:** The time taken by agents to answer calls, highlighting efficiency.

---

### 4. **Call Handling Efficiency Analysis**
Focused on operational efficiency, this section includes:
- **Average Speed of Answer by Date:** A line chart showing trends in answering speed over time.
- **Resolution Rate by Average Talk Duration:** A bar chart examining the relationship between talk duration and resolution rates.
- **Rate of Unanswered Calls by Time Interval:** A chart showing when the most calls go unanswered, segmented by time intervals.

---

### 5. **Topic-Based Analysis**
This section assesses the performance of calls based on specific topics:
- **Average Satisfaction Rate of Each Topic:** A bar chart displaying customer satisfaction rates for different call topics.
- **Resolution Rate of Each Topic:** The percentage of calls resolved for each topic category.

---

## Insights Gained
From this dashboard, several key insights can be derived:
1. **Call Handling Efficiency:** The average speed of answering calls and talk duration trends can help identify bottlenecks in handling customer queries.
2. **Agent Productivity:** By comparing metrics like resolved rate and talk duration, the dashboard provides a clear picture of agent performance, identifying top-performing and underperforming agents.
3. **Topic Trends:** The breakdown of calls by topic highlights the most frequent issues faced by customers, enabling the allocation of resources where needed.
4. **Customer Satisfaction:** The average satisfaction rate by topic reveals areas where service can be improved to enhance customer experience.

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
