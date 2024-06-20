![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/65e4257d-845a-43d7-aafc-2956ecae896d)MENTAL HEALTH ANALYSIS ON TWITTER -> every single analysis is present in Twitter_Analytics.ipynb, Twitter_Models.ipynb along with its Output
1) Overall Description of the Project
   
In the contemporary landscape of social media, where conversations unfold at a rapid pace, understanding the dynamics of mental health discourse has become an imperative task. The prevalence of discussions related to mental health on platforms like Twitter, Reddit serves as both an opportunity and a challenge. The problem at hand revolves around the need to decipher, analyze, and comprehend the intricate layers of user interactions and expressions concerning mental health. This multifaceted exploration is situated at the intersection of computer science and education, driven by the conviction that leveraging data science can offer profound insights into the digital landscape of mental well-being

2) Modeling and Implementation Details
   ![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/6536285b-5620-4751-bd78-32c31a50544f)
   ![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/45e48c3d-b136-4316-b90e-341a08e6dcf3)


3) Solution Approach
   
I.	Data Pre-processing

My journey commenced with data pre-processing, the cornerstone of my entire analysis. It aims to analyze social media posts employing NLP pre-processing. I undertook a meticulous process to refine the dataset, stripping away noise and ensuring the purity of my textual corpus. This module included the removal of mentions, a crucial step to enhance the focus on the core content of users' expressions. The cleanliness of the dataset set the stage for subsequent in-depth analyses.

II.	Temporal Analysis

The temporal analysis module unfolded as a captivating exploration into the temporal nuances of mental health discourse. I scrutinized the ephemerality of emotions, identifying peak activity periods and uncovering the subtle fluctuations in sentiment over days, weeks, and months. This module not only added a temporal dimension to our understanding but also provided insights into the dynamic nature of online discourse.

III.	Social Network Analysis

Diving into the social fabric of Twitter, the analysis extended to the friendships and connections within the platform. Within this module, I meticulously explored the social networks of both depressed and non-depressed users. Unraveling patterns within the label 0 (non-depressed) and label 1 (depressed) social circles, this analysis sheds light on the interconnectedness of individuals and the potential influence of emotional support networks on digital well-being.

IV. Naive Bayes Classification

In the heart of my solution approach lies the Naive Bayes classification module. This algorithm became my guiding compass in categorizing users into depressed and non-depressed labels based on their textual expressions. Grounded in probability theory, Naive Bayes provided a robust framework for discerning patterns within online conversations.

V.	Topic Modelling with LDA and Word2Vec

The module of topic modeling helps in my exploration, allowing me to discern the latent themes within textual conversations. Leveraging Latent Dirichlet Allocation (LDA) and Word2Vec, I embarked on a journey to uncover the underlying topics discussed by users. This intricate dance with language allowed me not only to categorize users but also to unveil the nuanced triggers and topics that permeate mental health discourse.

VI.	Transition from WhatsApp to Twitter

My project's evolutionary journey, initially rooted in a sentiment analysis exploration within WhatsApp, led to a transformative shift to the expansive landscape of Twitter. The limitations encountered within the WhatsApp ecosystem, including a lack of diverse conversations and limited features, spurred our transition. This strategic move enabled me to not only overcome shortcomings but also to harness the vast reservoir of data and diverse conversations that Twitter offers.

VII.	Analyzing Triggers and Topics of Interest: Unmasking Hashtag Dynamics

Within this module, I meticulously dissected the textual landscape, scrutinizing hashtags of paramount interest—#anxiety, #abuse, #depression, and more. The analysis not only provided insights into the prevalent triggers but also offered a nuanced understanding of the topics that resonate most profoundly within the online mental health community.

VIII.	Month-Wise Self-Confessions: Navigating the Cycles of Introspection

This granular exploration unfolded as a poetic examination of self-expression, month by month. The analysis journeyed through the temporal evolution of personal revelations, offering poignant insights into the cyclical nature of self-confessions within the online community. Month-wise analysis became a narrative tool, revealing the rhythm and flow of introspection on Twitter.

IX.	Conclusion
Each module contributes to my collective understanding of the digital landscape where vulnerability meets resilience. My approach is not just a technical endeavor; it is a testament to the power of interdisciplinary exploration, blending data science with empathy to navigate the complexities of human expression in the digital age.

4) Output Screenshots

Dataset:
![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/9ce89587-273a-49a8-b893-1cbd9d51ea00)

Text Analysis:

Q: How do self confessions about diagnosis of a particular disease vary throughout the year?

Analysis: Self confessions about diagnosis remained relatively low during the summer months and peaked towards the winter months as psychologists say winter triggers depression known as Seasonal affective disorder (SAD) is a type of depression that comes and goes in a seasonal pattern. SAD is sometimes known as "winter depression" because the symptoms are usually more apparent and more severe during the winter.

![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/5d7fc2b5-b438-4b7c-bc8b-95852d342628)

Activity period of top Hashtags :
![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/6b3491c2-e1be-42a7-bc70-a5cf9a7b4e3a)

Q: Investigate the temporal aspects of user behavior in the context of the most trending topics.

Ans: In context to my research, I selected a few hashtags closely related to mental health and emotional well being such as autism , #anxiety, #depression etc. and plotted their temporal frequencies .
Analysis: a) 0 to 6am #addiction is discussed in significant proportion
b)	#depression is discussed btw 0 to 6am and peaked at 4pm
c)	#anxiety during 2 to 5am

![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/9f070961-730e-442c-afa2-08adede228ae)

Q: What are the trending topics that people are willing to talk about ?

Ans : Extracting hashtags from the tweets then provide a comprehensive analysis for the same 
Analysis: Plotted a graph for all hashtags having a frequency greater than 10

![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/e58175ce-4348-4a7d-b934-0ef5766f1e1c)

Most Active Users : 

![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/b5361a36-fde7-4694-bb4f-57a3718af609)

Analysis: 10 Most retweeted post_text

![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/4d269b69-7ca8-4c13-a256-5efc186cd5e5)

Analysis: Depressed users are found most active during late night and evening while non depressed users are found most active during early morning and late night.

![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/407406bc-9b29-4c17-9c05-5588217bb2ea)

![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/1df74765-c377-4a48-837b-d01f70d8a536)

Q: Investigate the most active days of the week ?

Analysis: Non Depressed users were found most active during thursday while depressed were found most engaging during weekdays(mon,tue,wed,thurs).
We can conclude that depressed users are less active when they have some personal and family plans during weekends(fri,sat,sun) .

![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/f53fedf5-adf9-49a8-b844-5d02457ede97)

Q: How to detect the activeness of depressed and non depressed users along the years ?

Analysis: Non Depressed users were found most active during 2016-17 while depressed were showing some sort of activeness since 2009 and there was a sudden hike in their activeness during 2015 .

![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/86aca352-1088-4847-9c10-9353da02c899)
![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/ea8900a7-d2a3-4475-b22f-52944aa557d0)

Q: Investigate whether online friends are real or fake ?

Analysis: Depressed users come out with more friends than non depressed users. This allows us to conclude that more online friends does not ensure that the person is mentally healthy.

![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/99b501ae-06a1-4ba3-acd1-7a6ab7bb3189)

Q) Being depressed implies that people won’t follow you ?

Analysis: I found that depressed people have more followers than non depressed.
![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/14d761e5-0e45-4b8b-81f5-03c887603c4e)

MODELLING
Analysis: Top topics for the LDA Model
![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/e805863b-4ec0-44eb-b4f9-4483a6a2f013)
![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/17510b51-4b0b-4efd-80f3-7df35f8e7118)
![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/3e374573-6b55-4465-b95e-e968805ebee5)
![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/d4b43c68-d392-4bd8-a8a5-771e9a48c853)
![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/d57e2daa-06ae-40f0-92c3-65e6c7a96b13)
![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/2dcf96c8-e72c-476e-922d-7ce6c9160908)
![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/54b50aea-2e6d-43f7-ba08-19274d77a8cb)
![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/117fff13-da91-4a31-84c3-6b5129485a0f)

Analysis: Word Embeddings Visualization for #addiction Tweets with t-SNE
![image](https://github.com/NavyaSingh2003/mental_health_analysis_on_twitter/assets/110404553/b9a8cf7a-f374-4709-8a02-e94b82c4cc85)

































    
   
