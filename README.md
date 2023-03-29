# Towards Sentiment and Temporal Aided Stance Detection of Climate Change Tweets

#Abstract:
Climate change has become one of the most significant crises of our time. Public opinion on climate change is influenced by social media platforms such as Twitter, often divided into believers and deniers. In this paper, we propose a framework to classify a tweet’s stance on climate change (denier/believer). Existing approaches to stance detection and classification of climate change tweets either have paid little attention to the characteristics of deniers’ tweets or often lack an appropriate architecture. However, the relevant literature reveals that the sentimental aspects and time perspective of climate change conversations on Twitter have a major impact on public attitudes and environmental orientation. Therefore, in our study, we focus on exploring the role of temporal orientation and sentiment analysis (auxiliary tasks) in detecting the attitude of tweets on climate change (main task). Our proposed framework STASY integrates word- and sentence-based feature encoders with the intra-task and shared-private attention frameworks to better encode the interactions between task-specific and shared features. We conducted our experiments on our novel curated climate change CLiCS dataset (2465 denier and 7235 believer tweets), two publicly available climate change datasets (ClimateICWSM-2022 and ClimateStance-2022), and two benchmark stance detection datasets (SemEval-2016 and COVID-19-Stance). Experiments show that our proposed approach improves stance detection performance (with an average improvement of 12.14% on our climate change dataset, 15.18% on ClimateICWSM-2022, 12.94% on ClimateStance-2022, 19.38% on SemEval-2016, and 35.01% on COVID-19-Stance in terms of average F1 scores) by benefiting from the auxiliary tasks compared to the baseline methods. (https://www.sciencedirect.com/science/article/pii/S0306457323000626#fn4)

#Cite:
@article{UPADHYAYA2023103325,
title = {Towards sentiment and Temporal Aided Stance Detection of climate change tweets},
journal = {Information Processing & Management},
volume = {60},
number = {4},
pages = {103325},
year = {2023},
issn = {0306-4573},
doi = {https://doi.org/10.1016/j.ipm.2023.103325},
url = {https://www.sciencedirect.com/science/article/pii/S0306457323000626},
author = {Apoorva Upadhyaya and Marco Fisichella and Wolfgang Nejdl},
keywords = {Climate change, Stance detection, Sentiment analysis, Temporal orientation}
}
