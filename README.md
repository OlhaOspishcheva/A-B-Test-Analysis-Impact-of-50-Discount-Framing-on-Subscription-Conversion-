# A-B-Test-Analysis-Impact-of-50-Discount-Framing-on-Subscription-Conversion
## 📌 Project Overview
This project focuses on the end-to-end process of planning, executing, and analyzing an A/B test for a mobile application. The primary goal was to determine if framing a standard $4.99 weekly subscription as a "50% discount" (implying a original value of $9.98) would increase the conversion rate among new users.
## Key stages included:
1. Test Design: Formulating hypotheses and selecting primary/secondary metrics.
2. Planning: Calculating required sample sizes and test duration to ensure statistical power.
3. Execution: Splitting traffic 50/50 between a Control and Experimental group.
4. Analysis: Evaluating results using a Two-Proportion Z-Test and visualizing data trends.
## 🛠 Experimental Design 
### Hypotheses
#### Null Hypothesis ($H_0$): Adding a "50% discount" label to the $4.99 subscription screen does not affect the conversion rate.
#### Alternative Hypothesis ($H_1$): The "50% discount" label increases the conversion rate compared to the current design.
Test Parameters  
Primary Metric: Conversion Rate (CR) from paywall view to purchase.  
MDE (Minimum Detectable Effect): 2.5 percentage points (~15% relative lift).  
Target Audience: New users who completed onboarding and reached the subscription screen (approx. 34% of installs).  
Significance Level ($\alpha$): 0.05.Power ($1-\beta$): 0.80.3.   
#### Sample Size & DurationRequired 
Sample: ~2,510 users per group (5,020 total).  
Daily Traffic: ~680 users reaching the paywall.  
Actual Test Period: 21 days (from 2023-07-03 to 2023-07-25) to account for weekly seasonality.  
## 📈 Visualizations 
1. Conversion DistributionThe bar chart illustrates the significant increase in absolute conversions in Group B despite having nearly equal user counts.
2. Confidence IntervalsThe non-overlapping error bars for Group A (6.10%) and Group B (8.90%) confirm the statistical reliability of the performance gap.
3. Dynamics Over TimeTime-series analysis shows that Group B consistently outperformed Group A throughout the 21-day period, with a notable spike in conversion on the final day.
## 💡 Key Insights & Recommendations
1. Winner Identified: The "50% Discount" framing (Group B) is the clear winner with a 2.8 percentage point absolute lift.
2. Implementation: I recommend rolling out the Group B design to 100% of the user base.
3. Next Steps:Investigate the conversion spike on July 25th to identify potential external drivers.
Monitor long-term Retention and Refund Rates to ensure the "discount" framing maintains high user quality.
Test additional "Urgency" triggers (e.g., countdown timers) to further enhance the discount effect.

