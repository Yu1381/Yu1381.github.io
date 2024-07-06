---
layout: post
title: Deciphering Big Data
subtitle: Deciphering Big Data_e-portfolio
categories: data science
tags: [data science]
---

## unit1~6
The main outcome of Units 1-6 is teamwork, so I will write about that.
First, I will write about team creation. Unfortunately, I did not know anyone among the members, so I thought about how to form a team. There was talk that if no one was decided at the end, the remaining people would form a team, but I thought that I wanted to form a team myself. Among them, I chose to post an e-portfolio in which I wrote my self-introduction on the self-introduction form. Since I had time to spare, I wanted to form a team with people who saw it and were interested in me. I was able to form a team with the team members I would be forming with, and I was able to start the assignment earlier than the other teams. There were also other people who contacted me, but unfortunately I had already decided on a team, so I had to decline, and I felt sorry.

Next, we discussed how to proceed with the team assignment. This was because I thought it was important to confirm various understandings with each other first in order to proceed with the team assignment. Unfortunately, I live in Japan, which is very far from Europe, and due to the time difference, it seemed difficult to actively progress the assignment through video calls. Therefore, we both agreed to have a meeting based on chat and email.

As for the teamwork content, since one of my team members had experience, I asked him to set up the target customer and each entity. Since I work as a researcher at a chemical company, I am not familiar with this field, so I was very grateful for his experience. My work was about database selection and data cleaning. While I was working on the assignment, I thought I had prepared enough reference materials. However, as I learned more about each item in Units 7 to 10, I realized that I only had a superficial understanding of the overview. This is also related to the reflection on the assignment in Unit 11.
Although my final score was 58, I believe that I was able to complete a very meaningful team assignment, such as building a database in cooperation with my team members and understanding the overview of database construction.

## unit7
First, I organized the data so that each cell has a single value in the first normal form. Next, I eliminated partial functional dependencies in 2NF. I divided attributes that are not completely dependent on the primary key into separate tables. Since all attributes are directly dependent on the primary key at the time of 2NF, the requirements for the third normal form are met. I will use Python's Pandas and Numpy to convert data. Next, I will talk about primary and secondary keys. Primary keys allow you to manage each database table. Primary keys do not contain NULL and are the basis for establishing relationships between tables. Secondary keys are used to search and sort data. For referential integrity, you can use an SQL query to search for data and check whether results are obtained. For example, I can use the code in the Appendix. By using this, you can search for records where the primary key of Table1 and the foreign key of Table2 match, and check whether referential integrity is maintained. The benefits of normalization were confirmed in Susanne (2024).

## unit8
I learned about compliance in handling data using lecture texts and articles. The first thing I recognized was that data security and data compliance are different. Security is merely a minimum compliance with laws and security standards. Therefore, this cannot be called safe. GDPR, which is listed in GDPR EU (2018), is a standard for data compliance. Specific actions to be taken include access control, encryption in data storage, and the need to pay attention when discarding data. These are described in IBM (2023).

## unit9
In this unit, I learned about DBMS. This is generally MySQL (2024) and the like. The advantages of using it include ensuring data security, reducing redundancy, removing data inconsistencies, and ensuring data sharing. However, the disadvantages include the complexity for people who do not normally use DBMS and the cost of maintaining it. Therefore, it is important to design while thinking about future system maintenance. Also, when building a database, if you are a beginner, it is better to use something that is widely used. The reasons for this are that it has solid support, there are many solutions on the Internet in case of trouble, and there is a high possibility that it will continue to be upgraded in the future. There are four types of DBMS, including hierarchical database management systems.

## unit10
For example, Twitter Developer at X (N.D.) is an example of a Twitter API. First, I evaluate the security requirements. First, I consider authentication and authorization methods. Here, it is necessary to implement access control. Next, I consider data protection. Data transfer encryption and masking of confidential data are required. Next comes error handling. Finally, logging and auditing are required. The next step is to create Python code to connect to the API. For example, in this case, use the code described in the Appendix. Finally, create a specification for security requirements. Here is an example. First, authentication and authorization. The API key is stored as an environment variable and not hard-coded. Next, to protect data, all API requests are sent using HTTP/TLS. In addition, confidential data is masked and only the minimum amount of data required is obtained. Error handling is to log errors and display error messages to users that do not contain confidential information. Finally, logging and auditing is to log API access, monitor unauthorized access, and regularly audit logs. For these, I referred to Mendo (2024).

## unit11
First, I decided to create an executive summary based on the comments received in unit6. Since there were comments about the structure, I decided to create the text in paragraphs. In addition, since there was no information about legal compliance and compliance requirements in Unit6, I added information. There were also comments that the python code and other information had not been included, so I added them in the appendix. I also added more references and focused on making the logical development more persuasive. Furthermore, by using diagrams effectively, I was able to explain the relationships between tables, which are difficult to understand with text alone. I also wrote about database selection and data cleaning automation, and I believe that I was able to further strengthen my ability to propose to customers. I believe that I was able to learn important points about database construction that I did not understand at the end of Unit 6 through Units 7 to 10. I felt that the assignments in Units 7 to 10 were very meaningful because I was able to deepen my knowledge, which was only outlined at the end of Unit 6.

## Comparison of Unit 6 and Unit 11 projects
The information that was lacking in Unit 6 is as follows. First, the choice of database to use. I wrote that MySQL or PostgreSQL should be used, but I did not mention the choice. I also wrote about using Python, but did not write specific code. I regret that I could have provided more detailed information, even though there was a character limit. Therefore, I added more detailed information in Unit 11. For example, I wrote about database modeling diagrams. This allows us to visually grasp the relationships between each table, which I believe makes it easier to explain to customers. Next is database selection. I looked at Dmitry, N. (2024) to determine which one was appropriate for this example. Next, I wrote in detail about legal matters. It is important to mention that I am complying with laws and rules in order to reassure customers. I mentioned the need to comply with laws according to the country and industry in which I do business, as well as GDPR. I also added the importance of automating data entry and the security requirements that must be observed when using APIs. Data entry is inevitably dependent on people, so it is prone to mistakes. I mentioned that if manual entry is required, it must be automated to comply with the requirements of a third normalized table.

## Growth Section
1. About Database Construction
I learned how to build a database. In particular, I was able to learn how to normalize Excel data currently used in companies, especially denormalized Excel data, up to 3NF. It is said that only garbage results will come out of garbage data, but this is one way to avoid that. In addition, by completing the tasks in each unit, we were able to deepen our knowledge of each. For example, the assignment in Unit 7 allowed me to deepen my knowledge about data normalization and how to handle primary and foreign keys. Using these, I was able to further deepen the discussion in Unit 11.
I also learned about the types of databases and how to select them. I learned about the difference between NoSQL and RDBMS and how to choose them, as well as MySQL, which belongs to RDBMS, and PostgreSQL, which can be found on the Group, P. G. D. (2024) website. Each has its strengths and weaknesses, so it is necessary to choose appropriately.

2. Compliance with laws and compliance when handling data
I have been aware of GDPR and APPI in the Japanese Law (2003) for some time, and I have recognized their necessity. In addition, since I work for a company, I understand the importance of compliance requirements. However, I was not aware of compliance regarding data handling, so I felt that I would like to be careful about that in the projects I am involved in in the future. What I thought most about it was the need to be careful about data processing. When building a database, you need to think about how to build it and how to use it. However, if you do not decide on the processing method at that point, you must be careful that it will become a problem later.

3. About the use of APIs
The use of APIs increases the range of data and allows for deeper use. However, I felt that it is important that it is not just convenient, and learned that security requirements are important. Because APIs are used by many people, they are easily targeted by cyber attacks, and it is necessary to tighten data access, minimize data acquisition, monitor unauthorized access, manage logs, mask data, and encrypt data.

4. About the team project
This time, I was blessed with excellent team members, so I was able to proceed smoothly. I also personally think that it was a good point that we agreed on how to proceed with the theme at the beginning. Since my native language is Japanese, it was my first team project with an English speaker, but I think it went smoothly. His speed of progressing through the assignment was very fast, so I tried to progress my own assignment at the same time, but in the end, I had plenty of time until the submission, so I should have pursued the assignment more deeply while referring to Units 7 to 10. This reflection will be useful in future team projects.

## References
Susanne, M. (2024) Data Normalization: Definition, Importance, and Advantages. Available from: https://coresignal.com/blog/data-normalization/ [Accessed 30 June 2024].

IBM (2023). What Is Data Compliance? | IBM. Available at: https://www.ibm.com/topics/data-compliance [Accessed 30 June 2024].

GDPR. EU (2018). What is GDPR, the EU’s new data protection law?. Available at: https://gdpr.eu/what-is-gdpr/ [Accessed 30 June 2024].

MySQL.(2024) Available at: https://www.mysql.com/jp/ 

X .Use Cases, Tutorials, & Documentation | Twitter Developer Platform. Available at: https://developer.x.com/en [Accessed 6 July 2024].

Mendo, T. (2024). A Comprehensive Intro Guide to API Security. Available at: https://probely.com/blog/a-comprehensive-intro-guide-to-api-security/ [Accessed 30 June 2024].

Dmitry, N. (2024). MySQL vs Postgres in 2024. Available at: https://dbconvert.com/blog/mysql-vs-postgres-in-2024/ [Accessed 30 June 2024].

Group, P. G. D. (2024). PostgreSQL. Available at: https://www.postgresql.org/

Japanese Law (2003). Act on the Protection of Personal Information.  Available at: https://www.japaneselawtranslation.go.jp/en/laws/view/4241 [Accessed 30 June 2024].

## Appendix
Unit1~6 code

SELECT *

FROM Table1

INNER JOIN Table2

ON Table1.PrimaryKey = Table2.ForeignKey;


Unit10 code

import tweepy

import os

api_key = os.getenv('TWITTER_API_KEY')

api_secret_key = os.getenv('TWITTER_API_SECRET_KEY')

access_token = os.getenv('TWITTER_ACCESS_TOKEN')

access_token_secret = os.getenv('TWITTER_ACCESS_TOKEN_SECRET')

auth = tweepy.OAuthHandler(api_key, api_secret_key)

auth.set_access_token(access_token, access_token_secret)

api = tweepy.API(auth)

try:

    tweets = api.user_timeline(screen_name='twitter_username', count=10)
    
    for tweet in tweets:
    
        print(f"{tweet.user.name}: {tweet.text}")
        
except tweepy.TweepError as e:

    print(f"Error: {e}")
