---
layout: post
title: Machine learning
subtitle: Machine learning_e-portfolio
categories: data science
tags: [data science]
---
### Learning Artifacts and Contributions to Projects

## unit1~3
Here, I considered the impact of Industry 4.0 on the chemical industry. I then suggested the possibility that white-collar jobs could be taken over by AI (Cooban, 2024). In response, my colleagues suggested that new jobs could be created to replace the jobs lost, improving quality of life (Schwab Kl., 2016). They also suggested that technology could create time for growth and community (West, 2018). This multifaceted discussion helped me expand my knowledge.

## unit4
Since this project was mainly carried out as a team, I will summarize it in the Unit 6 section. 

## unit5
Jaccard coefficient is a measure of similarity between two sets. It can be calculated as follows.

A∩B: intersection of two sets.

A∪B: union of two sets.

Checking the table, it can be calculated as follows.

1, (Jack,Mary);
The number of intersections {1} is 1.
Whole parts 1, 0, and 1 appear throughout.
The unique value is 3.
Therefore, J(Jack,mary) is 1/3

2, (Jack,Jim);
The number of intersections {1} is 0.
Whole parts 1 and 0 appear throughout.
The unique value is 2.
Therefore, J(Jack,mary) is 0/2=0

3, (Jim,Mary);
The number of intersections {1} is 0.
Whole parts 1, 0, and 1 appear throughout.
The unique value is 2.
Therefore, J(Jack,mary) is 0/3=0

## unit6
In Unit 6, I used all my knowledge to tackle the team task. My role was to give opinions on the team policy, set the team name, and perform advanced data analysis. The assignment this time was to analyze various parameters of the Airhub in New York. However, for someone like me who is not familiar with New York, it is difficult to understand where the place is located even if the name of the place is mentioned. Therefore, by plotting the parameters on a visually appealing map, we were able to understand which areas are particularly expensive. This is an application of the content I implemented in my past assignments at University of Essex, and I think it is a great example of utilizing the knowledge I learned in the past.

## unit8~10
I mentioned the advantages and disadvantages of AI writing (ITRex, 2023, Hutson, 2021). The advantages were mainly improved efficiency and reduced costs, while the disadvantages were the accuracy of information and the danger of blindly accepting answers given by AI. My colleagues also offered opinions from various perspectives, but the consensus was that even with AI, the ultimate users are humans, so it is important that the humans who use it have the proper knowledge and morals.

## unit11
This was my first time implementing convolutional neural networks. Therefore, I had to start from the basics, but I was able to achieve a correct answer rate of nearly 90% with 20 layers using a CNN that I built myself. In addition, I was able to further improve the correct answer rate by using ResNet. I don't know how many situations I will use CNN in the future, but about 90% is enough for my usual work in chemistry research, but I would like to further study other models such as VGG and EfficientNet in the future. In addition, I think that by understanding the basic mathematics and learning the history of the development of CNN, I will be able to design more efficiently. For example, although it is difficult because I do not have an environment, I would like to confirm how overfitting occurs when the layers are increased to about 100 layers without using skip connection. I think that by doing so, I will be able to understand why ResNet was created.


### Final Project Evaluation and Ingenuity
## Unit6
# Self-evaluation of group activities
I believe that I was able to actively participate in group activities this time. When one of the team members first spoke to me, I responded quickly and contributed to the smooth progress of the group work. Considering that it was five days later that the other members responded, I believe that I was able to contribute to the group work quickly. In addition, since no one else had suggested using maps for analysis, I believe that I was able to add color to the final report. The people who will be looking at the analysis results in Unit 6 may not be data science specialists. To be honest, at that time, the results of statistical analysis and graphs may not be understood. I believe that my greatest contribution was using a tool that is familiar to the general public, such as maps.

## Unit11
# About the environment implementation
At first, I decided to use Google Colaboratory to run PyTorch. Since I am a beginner with PyTorch, I wanted to experiment with various models through various trial and error, but the free version has a time limit, and once the time limit is reached, you cannot try for a long time after that. It may not have been a problem for an experienced person who can implement efficiently, but it was not a friendly environment for a beginner like me. I usually enjoy games, so I own a GeForce RTX 3060 Ti, which is now a low-class consumer model. Therefore, I wondered if I could use this to build my own environment. I used both Pytorch and Tensorflow to build the environment, referring to various online articles. As a result, Pytorch was very easy to adapt to my environment, and I was able to create a model successfully. By doing so, I was able to create a relatively accurate model by trial and error with various execution conditions. This time, the dataset was CIFAR-10, which is a relatively small dataset, so I was able to learn it without any problems even with such a GPU, but it became clear that I would need to consider building the environment if I encounter a larger dataset in the future.

### What I learned throughout the unit
In terms of knowledge, I was able to solidify my foundation in machine learning, learn the basics and concepts of deep learning, and even implement it. In addition, I think that I was able to perform a more practical analysis by building the environment. I used both PyTorch and Tensorflow to check how easy they were to use. Both are commonly used tools, but I found pytorch easier to use. This time, we practiced image analysis, but I think that in the future I will be using other general deep learning methods more often than image analysis, so I think that this experience and knowledge will be very useful.

In addition to the knowledge, I learned the importance of efficiently working in group work and thinking about issues from the perspective of my own customers, such as readers of reports. My current job is research, so I do not directly interact with customers. However, at my company, I am told every day to work from the customer's perspective. Therefore, I am conducting research while thinking about virtual customers, and I think that this time was useful. In the future, I plan to resign and go on to a doctoral course, but I think I have once again realized the importance of learning from the customer's perspective in implementing research in society.

## References
Cooban, A. (2024) AI will shrink workforces within five years, say company execs | CNN Business. CNN. Available from: https://www.cnn.com/2024/04/05/business/ai-job-losses/index.html [Accessed 14 January 2025].

Schwab, Kl. (2016) The Fourth Industrial Revolution: what it means, how to respond. Available at: https://www.weforum.org/agenda/2016/01/the-fourth-industrial-revolution-what-it-means-and-how-to-respond/ [Accessed 14 January 2025]

West, D.M., 2018. The Future of Work: Robots, AI, and Automation. Brookings Institution Press. Available at: http://www.jstor.org/stable/10.7864/j.ctt1vjqp2g [Accessed 14 January 2025].

ITRex (2023) The pros and cons of generative AI. ITRex. Available from: https://itrexgroup.com/blog/pros-and-cons-of-generative-ai/ [Accessed 14 January 2025].
Hutson, M. (2021) Robo-writers: The rise and risks of language-generating AI. Nature, 591(7848), pp.22-25. DOI: https://doi.org/10.1038/d41586-021-00530-0.
