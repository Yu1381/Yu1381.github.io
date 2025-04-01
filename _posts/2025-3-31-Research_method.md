---
layout: post
title: Research Method
subtitle: Machine learning_e-portfolio
categories: data science
tags: [data science]
---
# Learning Artifacts and Contributions to Projects

## unit5
### Case Study 1: Cambridge Analytica (Confessorem, 2018, Kleinman, 2018)
In 2018, Cambridge Analytica conducted a simple quiz on Facebook. However, it was designed to collect data not only from the user but also from their friends. As a result, even though only 270,000 people took the test, data from 50 million users across the United States was collected. The results were then used for psychological analytics for political purposes such as elections.
-Ethical issues
The users who answered the survey did not consent to the use of not only their own data but also that of their friends.
-Social impact
It was suggested that the illegally collected data may have actually been used in the election of Trump.
-Legal impact
This incident was widely reported, and the need for strengthening personal information protection laws such as GDPR and stricter data protection regulations for companies has come under scrutiny.

### Case Study 2: NYU survey of MTA job violence (Troutman, 2024)
A survey of violence against employees of the New York City public transportation company, the MTA, conducted by researchers at New York University was published on Facebook, resulting in contamination of the database. NYU announced that 90% of general employees had experienced assault or harassment, but in reality, it was only about 11%.
-Ethical issues
The survey was poorly managed, and anyone was free to answer.
As a result, it contained a lot of data that did not reflect the actual situation.
-Social impact
The publication of incorrect data caused anxiety among citizens.
The fact that the results were published by the prestigious New York University in particular gave the results credibility, which is thought to be a factor.
-Legal impact
The research team requested a retraction.
The National Institutes of Health, which funded the study, and the research oversight group at New York University were notified of the issue.

## unit7~9
e-portfolio unit7_Hypothesis Testing worksheet

1 Introduction
In Unit 7, I learned the basic theory of hypothesis testing and t-tests using Excel. In particular, we learned how to check the homogeneity of variance using F-tests, and how to use one-sided and two-sided tests, and t-tests with and without pairing. We will describe the results of Exercise 7.1 to 7.5.

Exercise 7.1, 7.3 7.4
1 Data Overview
Data Set G: Data of impurities when processed with Agent1 and 2.
2 Test Procedure
This time, we will use a one-sided test to check whether Agent1 can remove impurities more effectively.
・Null hypothesis (H₀): μ₁ ≥ μ₂ (Agent 1 has the same performance as Agent2 or less)
・Alternative hypothesis (H₁): μ₁ < μ₂ (Agent1 is significantly more effective)
Check the homogeneity of variance using F-tests and perform t-tests
3 Results and interpretation
 
・Results of F-test
Since the p-value is 0.4886, which is greater than the significance level of 0.05, it can be determined that there is no significant difference in variance. Therefore, the variances of Agent 1 and Agent 2 are considered to be equal and are used in the t-test.

Results of the t-test
〇 Exercise 7.1
Even in the case of a one-sided test, the p-value is 0.1578, which is also larger than the significance level, so we cannot conclude that there is a significant difference.
〇 Exercise 7.3
In the case of a two-sided test, the p-value is 0.3156, which is larger than the significance level of 0.05, so we cannot reject the null hypothesis. In conclusion, there is no statistically significant difference.
From the above, Agent2 is slightly larger numerically, but at the 5% level, it cannot be said that there is a significant difference. In other words, it can be judged that it is within the range of chance error.
〇 Exercise 7.4
What happens if you switch the two-sided test performed in 7.3 to a one-sided test? If you switch to a one-sided test that shows that Agent1 is more effective, the one-sided test should theoretically be about half. However, it still does not fall below the significance level. Therefore, it is not a significant difference. However, choosing a one-sided test after the fact like this is not statistically valid.

Exercise 7.2, 7.5
1 Data overview
Test whether the average income of men exceeds that of women using the data from Data Set C
2 Test procedure
Use a one-sided test to examine whether men's income is higher than women's
H₀: μₘ ≤ μᶠ (men's income is lower than women's)
H₁: μₘ > μᶠ (men's income exceeds women's)








3 Results
・Results of F-test
The p-value is 0.2182, which is greater than 0.05. Therefore, the income variances of men and women can be considered equal. Therefore, the t-test uses a method that assumes equal variances.

Results of the t-test











The p-value of the one-tailed t-test is 0.00071, which is less than the significance level of 0.05. The null hypothesis can be rejected. Therefore, it can be said that the average income of men is statistically significantly higher than that of women.

e-portfolio unit7_Summary Measures worksheet
Exercise 6.1
The dataset shows weight loss data when eating Diet A and Diet B. 
Diet B resulted in a mean weight loss of 3.71 kg, with a standard deviation of 2.77 kg, suggesting a large degree of individual variability. Diet A, on the other hand, resulted in a weight loss of 5.341 kg, suggesting that Diet A resulted in a greater weight loss on average. The standard deviation of Diet A was 2.54 kg, which is slightly smaller, and we can see that the variability is also small.
Exercise 6.2
The median shows that exactly half of the participants in Diet B lost more than 3.745 kg. This is almost the same level as the mean, and we can see that the distribution is not significantly distorted. The quartiles are Q1=1.953 and Q3=5.404, indicating a large degree of variability. The interquartile range is 3.451 kg, which also indicates a large degree of individual variability. On the other hand, the median of Diet A was 5.642 kg, which is clearly higher than B, and the interquartile range was 3.285 kg, which is narrower than B. In other words, Diet B has a low median and a large variance, which indicates that the effect is low and there is a large individual difference.

Exercise 6.3
The dataset investigates the preferences for breakfast cereal brands in two areas. 
Compared to Area 1, Area 2 has high support for both Brands A and B. This means that Area 2 has high recognition of famous brands and/or high purchasing power.

Unit 9 - Charts Worksheet
Exercise 9.1 / 9.4
   
Objective: To show brand preferences in Areas 1 and 2 using a bar graph.
Exercise 9.2 / 9.5
 
The graphs shown in Exercise 9.1 are arranged side by side to make it easier to understand visually. We can see that the purchasing power of brands A and B is lower in Area 1 than in Area 2.
Exercise 9.3 / 9.6
 The histogram allowed me to check the distribution of data (variance, skewness, etc.). I was able to actually visually confirm the differences identified in the e-portfolio unit7_Summary Measures worksheet.
![image](https://github.com/user-attachments/assets/e2606357-4ba2-4562-9c9a-d246f237055d)


## Literture review and Research Proposal

## References
Confessore, N., 2018. Cambridge Analytica and Facebook: The Scandal and the Fallout So Far. The New York Times. [Accessed 18 February 2025].

Kleinman, Z., 2018. Cambridge Analytica: The story so far. The Guardian [online] Available at: https://www.bbc.com/news/technology-43465968, [Accessed 18 February 2025].

Troutman, M., 2024. NYU survey of MTA job violence was posted publicly on Facebook – and trolls may have taken over: “Mischievous respondents.” [online] Available at: https://nypost.com/2024/11/11/us-news/nyu-survey-of-mta-job-violence-was-posted-publicly-on-facebook-and-trolls-may-have-taken-over-mischevious-respondents/ [Accessed 18 February 2025].
![image](https://github.com/user-attachments/assets/73fab54b-300d-43c7-8204-c417628a7c7b)


