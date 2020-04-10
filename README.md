# Depreesion-domain-Lexicon
With Word2vec and LPA algorithm, a Chinese depreesion-domain lexicon with keywords can be built that will distinguish depressed users from non-depressed users on social media.

This is a research work I'm looking forward to helping depressed users online. See more about it at : http://preprints.jmir.org/preprint/17650

Files included:
Research results-----Depressive-domain Lexicon
Research datasets----Depressed and non-depressed microblogs
More details could be seen in the article.


An automatic construction of depressing-domain lexicon based on microblogs
=======================

Abstract

Background: According to the WHO report in 2017, there will be almost one depression patient among every 20 people in China. Diagnosis of depression, however, is usually a hard work in clinical detection due to slow observation, expensive cost and patient resistance. Meanwhile, with the rapid emergence of social networking site(SNS), people tend to share their daily life and disclose inner feelings online frequently, making it possible to have an effective mental detection using the rich text information. There are many achievements in English corpus, but for researches in China so far, extracting language features from online depression detection is in a relatively primary stage.

Objective: The purpose of this study is to propose an effective approach helping construct a depressing-domain lexicon. This lexicon will contain the language features that help identify depressed users on the social media. Our study compares the performance of detection with and without our lexicon.

Methods: We apply an auto-construction of depressing-domain lexicon using Word2Vec, semantic relationship graph and Label Propagation Algorithm. These two methods combined performed well in specific corpus during construction. The lexicon is obtained based on 111,052 Weibo microblogs from 1,868 depressed and non-depressed users. During depression detection, we consider 6 features, and use 5 classification methods to test the detection performance.

Results: Experiment results show that in terms of F1 value, our auto-construction method performs 1-6% better than the baselines, and is more effective and steadier. When applied to detection models like Logistic Regression and Support Vector Machine, our lexicon helps models outperform by 2-9%, and is able to improve the final accuracy in depression detection.

Conclusion: Our depressing-domain lexicon is proved to be a meaningful input of classification algorithms, providing linguistic insights in depressive status of test objects. We believe this lexicon can enhance early depression detection on social media. Future work will need to be carried out on a larger corpus and with more complex method.

Keywords: Depression detection, Depression diagnosis, Social media, Automatic construction, Domain-specific lexicon, Depressing lexicon, Label propagation

=======================
