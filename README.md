**Read Me File: "Analyzing Public Perception Towards Nashville School Shooting on Reddit through EMPATH and Topic Modeling" (Spring'23)**

---

### Research Overview:

This study, aims to analyze public sentiments towards the recent Nashville school shooting on Reddit. The research focuses on sentiment analysis using EMPATH and topic modeling through Latent Dirichlet Allocation (LDA).

### Research Questions:

1. How do individuals express their sentiments towards the recent school shooting in Nashville in the comments section of Reddit posts?
2. What are the key themes and topics related to the Nashville school shooting?

### Background:

The recent Nashville school shooting on March 27th, 2023, has prompted this study to understand public attitudes and perceptions about gun violence in schools. Previous studies on school shootings emphasize the significance of analyzing social media discussions for insights into public responses (Kalesan et al., 2018; Wang et al., 2016).

### Data:

- Data will be collected from Reddit using PRAW Python library, focusing on posts related to the Nashville school shooting.
- A minimum of 1000 comments will be extracted from a selected post.
- Data preprocessing involves removing URLs, HTML tags, and special characters.

### Method:

- NLTK's word_tokenize function will be used for text tokenization.
- Sentiment analysis will be performed using the EMPATH tool, assigning weights to emotional categories and generating an overall polarity score (-1 to +1).
- Latent Dirichlet Allocation (LDA) will be applied for topic modeling to identify key themes related to the Nashville school shooting.

### References:

1. Kalesan, B., Lagast, K., Villarreal, M., Pino, E., Fagan, J., & Galea, S. (2018). School shootings during 2013-2015 in the USA. Injury Prevention, 24(4), 261-267. DOI: 10.1136/injuryprev-2016-042162
2. Wang, N., Varghese, B., & Donnelly, P. D. (2016). A machine learning analysis of Twitter sentiment to the Sandy Hook shootings. DOI: 10.1109/eScience.2016.7870913

---

