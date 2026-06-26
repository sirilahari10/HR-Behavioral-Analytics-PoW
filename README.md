# 🧠 HR-Tech Product Analytics: Measuring the Impact of Behavioral Insights

*Turning ambiguous human behavior into rigorous product evidence.*

## The Context
In HR technology, product features are often built on "vibes" rather than evidence. This project simulates a core product analytics problem: **If we build an AI feature that gives managers behavioral insights about their team, does it actually move the needle on employee retention?**

## The Methodology: Survival Analysis
Simple A/B testing (e.g., comparing raw churn rates) often fails in HR because it ignores *when* an employee leaves. 
* **The Experiment:** A simulated cohort analysis of 2,000 managers. The treatment group received proactive "Behavioral Nudges," while the control group used standard workflows.
* **The Math:** I utilized **Kaplan-Meier Survival Analysis** and the **Log-Rank Test** to evaluate time-to-attrition.

## 📊 The Business Takeaway
The analysis proves a statistically significant reduction in 90-day churn ($p < 0.001$). 
* **For Product Strategy:** This moves the feature from a "nice-to-have" to a defensible ROI driver for GTM teams. 
* **For the User:** It proves that empathetic, science-backed management tools yield quantifiable business results.
