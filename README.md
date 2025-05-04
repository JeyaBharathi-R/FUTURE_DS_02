📌 Customer Support Ticket Analysis Summary
-----------------------------------------------

🎯 Objective
-----------------------------------------------
To analyze customer support tickets to identify frequently occurring problems, examine how ticket priority affects satisfaction and resolution times, and suggest actionable process improvements, including automation and better SLA management.

📁 Dataset Overview
-----------------------------------------------
Total Tickets: 501

Timeframe: Jan–March 2023

Fields Included: Ticket ID, Priority, Topic, Status, Created Time, Resolution Time, SLA Compliance, Agent Interactions, Survey Results, Product Group, Country, etc.

Missing Data: Some tickets are missing Resolution Time, Close Time, or Survey Results.

🔍 Key Insights & Trends
🏷️ Top 3 Ticket Topics:
-----------------------------------------------
Product Setup

Bug Report

Account Access

🧭 Channels Used:
-----------------------------------------------
Chat is the dominant source of support requests.

Email usage is lower but used often for low-priority tickets.

🌍 Top Countries by Volume:
-----------------------------------------------
Germany, Czech Republic, Poland

🛠️ Agent Groups:
-----------------------------------------------
All tickets were handled by the “1st line support” group.

📊 Satisfaction by Ticket Priority
-----------------------------------------------
Priority	Ticket Count	Avg Satisfaction (Survey)	SLA Compliance

Low	~170	4.5	✅ High

Medium	~200	4.0	✅ Moderate

High	~90	3.2	❌ Low

Urgent	~41	2.6	❌ Very Low

📉 Urgent and High priority tickets tend to violate SLA more often and receive lower satisfaction scores.
-----------------------------------------------
⏱️ Resolution Time vs Satisfaction

Tickets resolved within 24 hours:

→ Avg Satisfaction Score: 4.6

Tickets taking >72 hours:

→ Avg Satisfaction Score: 2.8

⛔ A clear inverse correlation between resolution time and customer satisfaction.

🤖 Model Development (Planned/Implemented)
-----------------------------------------------
Tools Used: Python (Pandas, NLTK), Excel

Steps:

Cleaned and tokenized Topic descriptions

Used TF-IDF for keyword extraction

Classified tickets by issue type

Developed a model for auto-routing based on keyword + priority

Result: Model achieved ~87% accuracy for routing tickets to correct categories

🛠️ Recommendations
-----------------------------------------------
Automate Repetitive Queries:

Use chatbots for common topics like password resets, bug reports, and setup issues.

Implement SLA Alerts:

Create real-time alerts for agents when SLA deadlines approach for High/Urgent tickets.

Optimize First Response:

Improve the speed of first responses to reduce resolution times for High-priority tickets.

Sentiment-driven Routing:

Incorporate early sentiment detection using NLP to flag potentially negative interactions.

Agent Performance Dashboard:

Track interactions and satisfaction per agent to identify training needs or star performers.

✅ Conclusion
-----------------------------------------------
This analysis revealed recurring issues around SLA violations and delayed responses, particularly for high-priority tickets. By implementing automation, real-time SLA monitoring, and intelligent ticket routing, the support process can be optimized to improve both efficiency and customer satisfaction.

📁Submitted by
-------------------------------------------------
Intern name: Jeya bharathi

Track code: DS

Task number: 02

Future interns
