# Essex Summer School 2022 — Quantitative Text Analysis

This page contains the materials for the Essex Summer School 2022 course *Quantitative Text Analysis*. Materials will be added as we go along.

Instructor: [Martijn Schoonvelde](http://mschoonvelde.com); TA: [Mehmet Erdem Arslan](mailto:m.e.arslan@essex.ac.uk)

You can find the syllabus [here](Syllabus_QTA.pdf).

## Communication

To facilitate communication and interaction throughout the course we will make use of a dedicated [Slack channel](https://essqta2022.slack.com).

## Slides

| Date        | Slides           |  Date        | Slides           |
| ------------- |:-------------:| ------------- |:-------------:|
| July  11   | [Link]( Slides/Slides_QTA_1.pdf ) | July  18   | [Link]( Slides/Slides_QTA_6.pdf)|
| July  12   | [Link](Slides/Slides_QTA_2.pdf ) | July  19   | [Link]()|
| July  13   | [Link](Slides/Slides_QTA_3.pdf ) | July  20   | [Link]()|
| July  14   | [Link](Slides/Slides_QTA_4.pdf)  | July  21   | [Link]()|
| July  15   | [Link](Slides/Slides_QTA_5.pdf)| July  22   |  [Link]() |


## Lab Sessions

| Date        | Link           | Solutions           |    
| ------------- |:-------------:|:-------------:|
| July  11   | [Script]( Lab_sessions/Day_1/Lab_Session_QTA_1.md ) | [Exercise solution](Lab_sessions/Day_1/Lab_Session_QTA_1_Answers.md) |
| July  12   | [Script](Lab_sessions/Day_2/Lab_Session_QTA_2.md ) | [Exercise solution]( Lab_sessions/Day_2/Lab_Session_QTA_2_Answers.md) |
| July  13   | [Script](Lab_sessions/Day_3/Lab_Session_QTA_3.md ) | [Exercise solution](Lab_sessions/Day_3/Lab_Session_QTA_3_Answers.md) |
| July  14   | [Script](Lab_sessions/Day_4/Lab_Session_QTA_4.md ) | [Exercise solution](Lab_sessions/Day_4/Lab_Session_QTA_4_Answers.md) |
| July  15   | [Script](Lab_sessions/Day_5/Lab_Session_QTA_5.md) | [Exercise solution](Lab_sessions/Day_5/Lab_Session_QTA_5_Answers.md) |
| July  18   | [Script](Lab_sessions/Day_6/Lab_Session_QTA_6.md) | [Exercise solution]() |
| July  19   | [Script]() | [Exercise solution]() |
| July  20   | [Script]() | [Exercise solution]() |
| July  21   | [Script]() | [Exercise solution]() |
| July  22   | [Script]() | [Exercise solution]() |

<!-- ## Flash talks

| Name        | Link           | 
| ------------- |:-------------:| 
 -->

## Acknowledgements

For some code in the lab scripts, I made use of materials by Jos Elkink [here](http://www.joselkink.net/files/POL30430_Spring_2017_lab11.html), and [here](http://www.joselkink.net/files/POL30430_Spring_2017_lab12.html), and Wouter van Atteveldt [here](http://vanatteveldt.com/ccs_lda/) and [here](http://vanatteveldt.com/learningr/). The setup of the code practice scripts follows the structure in Welbers, K., Van Atteveldt, W., & Benoit, K. (2017) (see below for citation). I thank Stefan Müller for sharing with me his lab session materials for his QTA course. Thanks to all.

## Course schedule


*Day 1 - July 11*

 - **Lecture**: What is quantitative text analysis? What will you learn in this course? 
 
-  **Lab**: Working in RStudio Cloud. Working with libraries in R. Working with RMarkdown. 

- **Readings**
  - Benoit (2020). Text as Data: An Overview. Handbook of Research Methods in Political Science and International Relations. Ed. by L. Curini and R. Franzese. Thousand Oaks: Sage: 461–497.
  - Grimmer, J., & Stewart, B. M. (2013). Text as data: The promise and pitfalls of automatic content analysis methods for political texts. Political Analysis, 21(3), 267–297.

*Day 2 - July 12*

-	**Lecture**: Core assumptions in quantitative text analysis. Considering issues of measurement and validation. 

-	**Lab**: Regular expressions. Working with strings. Creating a dataframe. 

- **Readings**:
  -  Welbers, K., Van Atteveldt, W., & Benoit, K. (2017). Text analysis in R. Communication Methods and Measures, 11(4), 245–265.
  
  - Baden, C., Pipal, C., Schoonvelde, M. & van der Velden, M.A.G., (2022). Three Gaps in Com- putational Text Analysis Methods for Social Sciences: A Research Agenda. Communication Methods and Measures, 16(1): pp. 1–18.


*Day 3 - July 13*

-	**Lecture**: Going from text to data. Preprocessing and feature selection. Deciding on the unit of observation and unit of analysis. 

-	**Lab**: Importing textual data into R. Creating a corpus of documents and adding metadata to it. Creating a document-feature matrix. 

- **Readings**:
  -  Denny, M.J. & Spirling, A., (2018). Text preprocessing for unsupervised learning: Why it matters, when it misleads, and what to do about it. Political Analysis, 26(2): pp.168–189.
  
  - Benoit, K., Watanabe, K., Wang, H, Nulty, P., Obeng, A., Müller, & Matsuo, A. (2018).
Quanteda: An R package for the quantitative analysis of textual data. Journal of Open Source Software, 3(30), 774.

*Day 4 - July 14*

-	**Lecture**: Comparing documents in a corpus. Combining linguistic features and social science theories. 

-	**Lab**: Estimating similarity, readability and complexity of documents. 

- **Readings**
  -  Peterson, A. & Spirling, A., (2018). Classification accuracy as a substantive quantity of interest: Measuring polarization in Westminster systems. Political Analysis, 26(1): pp. 120– 128.

  - Cross, J. & Hermansson, H., (2017). Legislative amendments and informal politics in the European Union: A text reuse approach. European Union Politics, 18(4): 581–602.

*Day 5 - July 15*

-	**Lecture**: What are dictionaries and how can we validate them? Sensitivity and specificity. 

-	**Lab**: Creating a dictionary and applying it to a document-feature matrix. 

- **Readings**:
  -  Pennebaker J. & King, L. (1999) Linguistic styles: language use as an individual difference. Journal of Personality and Social Psychology, 77(6), 1296–1312.
  
  - Young, L., & Soroka, S. (2012). Affective news: The automated coding of sentiment in political texts. Political Communication, 29(2), 205–231.

*Day 6 - July 18*

-	**Lecture**: Human coding and document classification using supervised machine learning.

-	**Lab**: Binary classification of documents using a Naïve Bayes classifier.

- **Readings**:
  -  Daniel Jurafsky and James H. Martin (2020). Speech and Language Processing: An Introduction to Natural Language Processing, Computational Linguistics, and Speech Recognition. 3rd edition: Chapter 4.
  
  - Müller, S., (2020). “Media coverage of campaign promises throughout the electoral cycle.” Political Communication: 1–23.

*Day 7 - July 19*

-	**Lecture**: Supervised, semi-supervised and unsupervised approaches to place text on an underlying (political) dimension. 

-	**Lab**: Wordfish, Wordscores and Latent Semantic scaling.

- **Readings**:

  - Slapin J. & Proksch S. (2008). A scaling model for estimating time-serial positions from texts. American Journal of Political Science 52, 705–722.
  - Hjorth, F., Klemmensen, R., Hobolt, S., Hansen, M. E., & Kurrild-Klitgaard, P. (2015). Computers, coders, and voters: Comparing automated methods for estimating party positions. Research & Politics, 2(2).

*Day 8 - July 20*

-	**Lecture**: Understanding topic models. Discussing their pros and cons. 

-	**Lab**: Latent Dirichlet Allocation (LDA) and Structural topics models (STM).

- **Readings**:
  - Blei, D. M. (2012). Probabilistic topic models. Communications of the ACM, 55(4), 77–84.
  
  - Roberts, M et al. (2014). Structural topic models for open-ended survey responses. American
Journal of Political Science, 58(4), 1064–1082.

*Day 9 - July 21*

-	**Lecture**: New developments in data. Images as data. Automated speech recognition. Machine translation.

-	**Lab**: Using APIs for generating useful textual data. 

- **Readings**:
  - Proksch, S.O., Wratil, C. and Wäckerle, J., (2019). Testing the validity of automatic speech recognition for political text analysis. Political Analysis, 1–21
  
  - De Vries, E., Schoonvelde, M. & Schumacher, G., (2018). No longer lost in translation: Evidence that Google Translate works for comparative bag-of-words text applications. Political Analysis, 26(4), 417–430.
  
  - Casas, A. & Williams, N.W., (2019). Images that matter: Online protests and the mobilizing role of pictures. Political Research Quarterly, 72(2): 360–375.

*Day 10 - July 22*

-	**Lecture**: Word embeddings. Concluding remarks. 

-	**Lab**: Exploring a pre-trained word embeddings model. 

- **Readings**:
  - Rudkowsky, E., Haselmayer, M., Wastian, M., Jenny, M., Emrich, S. & Sedlmair, M., (2018). More than bags of words: Sentiment analysis with word embeddings. Communication Methods and Measures, 12(2-3), 140–157.
  
  - Rodman, E., (2020). A Timely Intervention: Tracking the Changing Meanings of Political Concepts with Word Vectors. Political Analysis, 28(1): pp. 87–111.


