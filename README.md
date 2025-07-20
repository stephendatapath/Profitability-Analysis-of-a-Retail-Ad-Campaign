# Profitability-Analysis-of-a-Retail-Ad-Campaign
My Role: Marketing Data Scientist.

### PROBLEM
The business was spending heavily on ads, but profits weren’t matching up. Some campaigns brought massive losses, and there was no clear process to detect underperformers early.

### Goals
Identify ad campaigns causing major financial losses.
Test if high-loss campaigns still bring in strong revenue.
Make data-driven recommendations for better ad budgeting.

### What I Did
Using statistical analysis and regression techniques, I discovered five ad campaigns with Z-scores below –3. These outliers, especially in July and November, showed very high impressions and clicks, yet had severe losses, far beyond what’s normal. They needed urgent attention.

I ran a hypothesis test comparing two groups:
Group A: High-loss campaigns
Group B: Normal campaigns

The results showed a p-value of 0.0165, meaning there's only a 1.65% chance that the revenue difference between both groups was random.
📌 Group A (High-loss): Avg revenue = $22,658.40
📌 Group B (Normal): Avg revenue = $2,425.00

Since the p-value is below 0.05, I rejected the null hypothesis and concluded:
High-loss campaigns actually generate significantly more revenue than normal ones.

### Recommendations
1. Rework or pause coupon-heavy campaigns, especially on mobile.
2. Prioritize high-performers like Black Friday/Cyber Monday and competitor-focused ads.
3. Run monthly Z-score checks to catch outliers early.
4. Adopt performance-based budgeting—fund top performers more.
5. Set up monthly A/B tests to learn and iterate consistently.
