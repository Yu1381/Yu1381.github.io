---
layout: post
title: Research_method
subtitle: Research_method_e-portfolio
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
1 Introduction
In Unit 7, I learned the basic theory of hypothesis testing and t-tests using Excel. In particular, we learned how to check the homogeneity of variance using F-tests, and how to use one-sided and two-sided tests, and t-tests with and without pairing. We will describe the results of Exercise 7.1 to 7.5.

### Exercise 7.1, 7.3 7.4
1 Data Overview
Data Set G: Data of impurities when processed with Agent1 and 2.

2 Test Procedure
This time, we will use a one-sided test to check whether Agent1 can remove impurities more effectively.

・Null hypothesis (H₀): μ₁ ≥ μ₂ (Agent 1 has the same performance as Agent2 or less)

・Alternative hypothesis (H₁): μ₁ < μ₂ (Agent1 is significantly more effective)

Check the homogeneity of variance using F-tests and perform t-tests
3 Results and interpretation

 <img width="286" alt="image" src="https://github.com/user-attachments/assets/44acebaa-a354-4e4b-a1c5-65c09bdc04a8" />
 
・Results of F-test

Since the p-value is 0.4886, which is greater than the significance level of 0.05, it can be determined that there is no significant difference in variance. Therefore, the variances of Agent 1 and Agent 2 are considered to be equal and are used in the t-test.

Results of the t-test

<img width="400" alt="image" src="https://github.com/user-attachments/assets/77878ad7-5b62-4010-9861-751c65e83fd0" />


〇 Exercise 7.1


Even in the case of a one-sided test, the p-value is 0.1578, which is also larger than the significance level, so we cannot conclude that there is a significant difference.


〇 Exercise 7.3


In the case of a two-sided test, the p-value is 0.3156, which is larger than the significance level of 0.05, so we cannot reject the null hypothesis. In conclusion, there is no statistically significant difference.
From the above, Agent2 is slightly larger numerically, but at the 5% level, it cannot be said that there is a significant difference. In other words, it can be judged that it is within the range of chance error.


〇 Exercise 7.4


What happens if you switch the two-sided test performed in 7.3 to a one-sided test? If you switch to a one-sided test that shows that Agent1 is more effective, the one-sided test should theoretically be about half. However, it still does not fall below the significance level. Therefore, it is not a significant difference. However, choosing a one-sided test after the fact like this is not statistically valid.

### Exercise 7.2, 7.5
1 Data overview

Test whether the average income of men exceeds that of women using the data from Data Set C

2 Test procedure

Use a one-sided test to examine whether men's income is higher than women's
H₀: μₘ ≤ μᶠ (men's income is lower than women's)
H₁: μₘ > μᶠ (men's income exceeds women's)

<img width="219" alt="image" src="https://github.com/user-attachments/assets/3f0a8764-9094-45e5-956e-c2ca8e7ac69c" />

3 Results

・Results of F-test

The p-value is 0.2182, which is greater than 0.05. Therefore, the income variances of men and women can be considered equal. Therefore, the t-test uses a method that assumes equal variances.
Results of the t-test

<img width="256" alt="image" src="https://github.com/user-attachments/assets/2370fe8a-c4c6-4f54-991e-7c6340a34c25" />

The p-value of the one-tailed t-test is 0.00071, which is less than the significance level of 0.05. The null hypothesis can be rejected. Therefore, it can be said that the average income of men is statistically significantly higher than that of women.
### e-portfolio unit7_Summary Measures worksheet
### Exercise 6.1

<img width="145" alt="image" src="https://github.com/user-attachments/assets/322d6a3e-b380-4458-a9e1-9ed63567ffaa" />

The dataset shows weight loss data when eating Diet A and Diet B. 

Diet B resulted in a mean weight loss of 3.71 kg, with a standard deviation of 2.77 kg, suggesting a large degree of individual variability. Diet A, on the other hand, resulted in a weight loss of 5.341 kg, suggesting that Diet A resulted in a greater weight loss on average. The standard deviation of Diet A was 2.54 kg, which is slightly smaller, and we can see that the variability is also small.
### Exercise 6.2
The median shows that exactly half of the participants in Diet B lost more than 3.745 kg. This is almost the same level as the mean, and we can see that the distribution is not significantly distorted. The quartiles are Q1=1.953 and Q3=5.404, indicating a large degree of variability. The interquartile range is 3.451 kg, which also indicates a large degree of individual variability. On the other hand, the median of Diet A was 5.642 kg, which is clearly higher than B, and the interquartile range was 3.285 kg, which is narrower than B. In other words, Diet B has a low median and a large variance, which indicates that the effect is low and there is a large individual difference.
### Exercise 6.3
The dataset investigates the preferences for breakfast cereal brands in two areas. 
Compared to Area 1, Area 2 has high support for both Brands A and B. This means that Area 2 has high recognition of famous brands and/or high purchasing power.

<img width="145" alt="image" src="https://github.com/user-attachments/assets/17f1918f-5d4a-4942-922d-f113a3ff0feb" />

### Unit 9 - Charts Worksheet
Exercise 9.1 / 9.4

<img width="200" alt="image" src="https://github.com/user-attachments/assets/e379912f-04a1-4677-98fa-434ed0a2e7bb" /><img width="197" alt="image" src="https://github.com/user-attachments/assets/462b02a6-332a-4c12-9659-3db1c98da86d" />

Objective: To show brand preferences in Areas 1 and 2 using a bar graph.
### Exercise 9.2 / 9.5
The graphs shown in Exercise 9.1 are arranged side by side to make it easier to understand visually. We can see that the purchasing power of brands A and B is lower in Area 1 than in Area 2.

<img width="425" alt="image" src="https://github.com/user-attachments/assets/093d1f00-0d43-4853-b2b7-b1a934662714" />

### Exercise 9.3 / 9.6
 The histogram allowed me to check the distribution of data (variance, skewness, etc.). I was able to actually visually confirm the differences identified in the e-portfolio unit7_Summary Measures worksheet.
 
<img width="218" alt="image" src="https://github.com/user-attachments/assets/8b5c9db9-2220-4952-a66a-6b22b04afb3a" />

<img width="226" alt="image" src="https://github.com/user-attachments/assets/e51101b3-bed3-4278-879c-d48554008de4" />



## Literture review and Research Proposal

This time, I selected Distance Education (DE) as the theme for the literature review and research proposal. The literature review was conducted by subdividing the theme, focusing on existing reviews. I believe that I was able to conduct a comprehensive literature review by considering it from multiple perspectives, such as people and systems. 

The research proposal considered improving the quality of University of Essex Online. As a result of the literature review, research on DE itself has been conducted comprehensively (Domingues et al. 2023, Fojtík 2018), so we decided to explore ways to actually utilize it. Therefore, it is important for the research method itself to follow previous methods, and it will be carried out mainly based on the literature review we conducted. Among them, the impact of COVID-19 was suggested in many literature as a background (Masalimova et al., 2022). Next, I extracted the elements obtained from the literature review and thought that they could be used in interviews and questionnaires. In particular, I thought that a deeper understanding could be achieved by using both quantitative and qualitative research (Streefkerk, 2019). I also created a specific research schedule using a Gantt chart, and was able to establish a system to conduct research more efficiently. 

Furthermore, by listing future research that should be conducted at the end of the paper, it was possible to consider not only this research but also future developments.

## References
Confessore, N., 2018. Cambridge Analytica and Facebook: The Scandal and the Fallout So Far. The New York Times. [Accessed 18 February 2025].

Kleinman, Z., 2018. Cambridge Analytica: The story so far. The Guardian [online] Available at: https://www.bbc.com/news/technology-43465968, [Accessed 18 February 2025].

Troutman, M., 2024. NYU survey of MTA job violence was posted publicly on Facebook – and trolls may have taken over: “Mischievous respondents.” [online] Available at: https://nypost.com/2024/11/11/us-news/nyu-survey-of-mta-job-violence-was-posted-publicly-on-facebook-and-trolls-may-have-taken-over-mischevious-respondents/ [Accessed 18 February 2025].

Domingues, S., Souza, R.D.C.D., Melo, C.S.B.D. and Cruz, B.M.D. (2023) ‘Adaptation of Students Who Started Higher Education during Remote Teaching in Minas Gerais’, Educação e Pesquisa, 49, e266765.

Fojtík, R. (2018) ‘Problems of Distance Education’, International Journal of Information and Communication Technology Education, 7, pp. 14–23.
Masalimova, A.R., Khvatova, M.A., Chikileva, L.S., Zvyagintseva, E.P., Stepanova, V.V. and Melnik, M.V. (2022) ‘Distance Learning in Higher Education During COVID-19’, Frontiers in Education, 7, 822958.

Streefkerk, R. (2019) Qualitative vs. Quantitative Research | Differences, Examples & Methods. Scribbr. Available at: https://www.scribbr.com/methodology/qualitative-quantitative-research/ (Accessed: 31 March 2025).

