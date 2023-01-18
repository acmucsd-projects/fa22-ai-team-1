# The Hacktivists
## Supreme Court Predictor
![image](https://user-images.githubusercontent.com/86854157/213305775-61c3d014-33db-4316-a4ae-07cbb8a7332f.png)
*Image from Wikipedia*
### Table of Contents
* [Background](https://github.com/acmucsd-projects/fa22-ai-team-1/blob/main/README.md#background)
* [Dataset](https://github.com/acmucsd-projects/fa22-ai-team-1/blob/main/README.md#dataset)
* [Project and Technologies](https://github.com/acmucsd-projects/fa22-ai-team-1/blob/main/README.md#project--technologies)
* [Presentation](https://github.com/acmucsd-projects/fa22-ai-team-1/blob/main/README.md#presentation)
* [Authors](https://github.com/acmucsd-projects/fa22-ai-team-1/blob/main/README.md#authors)

### Background
Debates around the legitimacy of the Supreme Court and the uproar over Roe v. Wade towards the later half of 2022 influenced us greatly as we brainstormed ideas for our introductory machine learning project. As we pored through our options and studied the uses of AI, we arrived upon this project: can the predictive power of machine learning be used to predict the outcomes of Supreme Court cases?

### Dataset
![image](https://user-images.githubusercontent.com/86854157/213307112-7b2fbc98-d049-4423-9af3-405c7d3855c1.png)
*Image from The Supreme Court Database Homepage* <br /> <br />
After some searching, we selected [Washington University's Modern Dataset](http://scdb.wustl.edu/data.php) of past Supreme Court Cases for its breadth of data values and relevance to our current times. <br />
Of the available dataset variations, we chose Case-Centered Data, which focused on the outcomes of specific cases. 

### Challenges
The first challenge we encountered was figuring out our dataset. Because the outcome of a SCOTUS case is determined by so many different variables, there didn't appear to be many correlations between them at first.
<br /> <p align="center"> <img src="https://user-images.githubusercontent.com/86854157/213310071-bf3acf1d-b520-496b-b5e2-6eeb4d4434ff.png" width="600"> </p> <br />
We also had to do quite a bit of processing on the values in the dataset, since there were many null and non-Integer values.
<br /> <p align="center"> <img src="https://user-images.githubusercontent.com/86854157/213310173-c7aaf4ee-06a2-4fe6-91a7-4f374f982f37.png" width="400"> </p> <br />
Because none of us had have a strong foundation in law, much of the legal terminology also required research on our ends, so we could understand just what the dataset conveyed.
After we overcame the first hurdle, we began building our models. We encountered the most errors when optimizing our model through K-Fold Cross Validation, which led to us doing many tasks manually.
Lastly, as this was a first brush with AI and ACM Projects for many of us, we definitely had to work hard to manage our time and polish our skills!

### Project & Technologies
![image](https://user-images.githubusercontent.com/86854157/213307361-5441f828-9b43-40bb-957c-546a5deba0c5.png)
*Image from Deepnote's Homepage* <br /> <br />
All of our work was done on Deepnote, an virtual platform with processing power that allows for real-time collaboration. We created several notebooks in this environment: the first hosts our initial data loading, processing, and feature selection attempts (including our heatmap). The deep-learning notebook includes our neural network, and the pipeline notebook includes our exploratory data analysis, the sklearn pipeline we built for data processing, and our supervised learning models as well as their results. 

View it and see the results here:  
#### [Supreme Court Predictor](https://deepnote.com/join-team?token=02d34e715c9e4f6)

### Presentation
Check out our full process description and list of models right [here](https://docs.google.com/presentation/d/1qANpLZvhv5F0lOkbUxtlJU5UF4KqsDzuy0Dy6E2BG-0/edit?usp=sharing)!

### Authors
Ada He | [LinkedIn](https://www.linkedin.com/in/adahe0908/) | [Github](https://github.com/adahe8) <br />
Nitya Pillar | [LinkedIn](https://www.linkedin.com/in/nitya-p-087b431ab) | [Github](https://github.com/nbpillai) <br /> 
Jenny Mar | [LinkedIn](www.linkedin.com/in/jenny-mar-13158225a) | [Github](https://github.com/jennymar) <br />
Han Hoang | [LinkedIn](https://www.linkedin.com/in/hanhoangia/) ! [Github](https://github.com/hanhoangia) <br />
Serena Cheng | [LinkedIn](www.linkedin.com/in/serenachen6) | [Github](https://github.com/schen126)  <br />
Rushil Chandrupatla | [LinkedIn](https://www.linkedin.com/in/rushil-chandrupatla-1aaa34205/) | [Github](https://github.com/rushilcs)  <br />
