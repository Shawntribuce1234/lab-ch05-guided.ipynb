# lab-ch05-guided.ipynb
Monte Carlo Engine — Probability & Simulation
Objective
In this lab, I used Python and NumPy to explore probability through simulations and understand how random events behave over time.
Methodology
- Simulated 10,000 coin flips and plotted the running percentage of heads to observe the Law of Large Numbers.
- Simulated 10,000 Monty Hall games to compare the probability of winning by switching versus staying.
- Simulated disease screening tests for 100,000 people using a 1% disease prevalence, 95% sensitivity, and 90% specificity.
- Used Monte Carlo simulations to calculate Value at Risk (VaR) and Expected Shortfall (ES) for a $1 million portfolio.
- Estimated pi using random samples and examined how simulation error decreases as the sample size increases.
Key Findings
- Coin Flips: As I increased the number of flips, the percentage of heads got closer to 50%, demonstrating the Law of Large Numbers.
- Monty Hall: Switching doors won approximately 67% of games, compared to 33% when staying.
- Disease Screening: Only about 9.2% of positive test results came from people who actually had the disease. This showed me how much the prevalence of a disease affects the accuracy of a positive result.
- Value at Risk (VaR): The 95% VaR was approximately $19,494, meaning the portfolio would lose more than this amount on about 5% of simulated days.
- Expected Shortfall (ES): The 95% ES was approximately $24,230, representing the average loss during the worst 5% of simulated days.
- Monte Carlo Error: I found that simulation error decreases at a rate of approximately \(1/\sqrt{n}\), meaning larger simulations generally produce more accurate estimates.
Conclusion
This lab helped me better understand how probability works in real-world situations. My biggest takeaway was that running more simulations can improve accuracy, but understanding the probabilities behind the results is just as important.
