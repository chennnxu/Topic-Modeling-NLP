# Topic Modeling of [PyConDe & PyData Berlin 2023](https://2023.pycon.de/) Sessions 

As a first-time attendee of such a great conference, I would say I am so lucky to get the grant provided by the Diversity Committee. It made it possible for me to attend this event and gain valuable insights into the latest trends and innovations in the field and make connection to over 1200 people with same interets. That's amazing!

<div align = "center">
<img src="1.png" width = "400" alt="berlin" align=center />
<img src="2.png" width = "400" alt="berlin" align=center />
</div>
<div align = "center">
<img src="3.png" width = "400" alt="berlin" align=center />
<img src="4.png" width = "400" alt="berlin" align=center />
</div>

After back from the event, I think why not using the new things I have learned from the conference to make a summary of it. Then I decide to use spaCy to do topic modelling for all the sessions in PyConDe & PyData Berlin 2023. Actually every seesion already has manually assigned track('topic') to it. So next what is the differece of the manual assigned track and topic assigned using topic modeling algorithm. I will do a small project on it to figure it out.

<!-- ### Algorithm

Topic modeling is an unsupervised machine learning technique that extract hidden topics from text. The algorithm I am going to use is LDA. -->

<!-- ### Analysis process -->

### Step 0 Get the Data

I got the session json data from the PyConDe & PyData Berlin 2023 online. And then I need to preprocess the data from json to pandas DataFrame, and filter the attributes I am interested in, e.g. title, track and abstract etc.. 

We can see from the data that there are total 115 sessions and there are totally 22 manually assigned tracks and their distribution are shown as follows.
```
PyData: Natural Language Processing                                15
PyCon: Programming & Software Engineering                          15
Sponsor                                                            12
PyData: PyData & Scientific Libraries Stack                        10
PyData: Machine Learning & Stats                                   10
PyData: Data Handling                                               9
PyCon: DevOps & MLOps                                               8
PyCon: Python Language                                              4
Plenary                                                             4
PyData: Deep Learning                                               4
General: Ethics & Privacy                                           3
PyCon: Libraries                                                    3
PyData: Jupyter                                                     3
PyCon: Testing                                                      3
General: Others                                                     2
General: Python & PyData Friends                                    2
PyData: Computer Vision                                             2
General: Community, Diversity, Career, Life and everything else     2
PyData: Visualisation                                               1
PyCon: Django                                                       1
PyCon: Web                                                          1
General: Infrastructure - Hardware & Cloud                          1
```

### Step 1 SpaCy Pipeline
Next I am going to use the spaCy to topic model the sesssion which is based the abstract of each session.



### Step 2 Topic distribution and Difference

### Links
[1] [Github Full Notebook](pyconde_analysis.ipynb)

[2] [spaCy](https://spacy.io/)

<!-- [3] [Prodigy](https://prodi.gy/)

### References
[1] [Topic Modelling in Python with spaCy and Gensim](https://towardsdatascience.com/topic-modelling-in-python-with-spacy-and-gensim-dc8f7748bdbf)

[2] [Topic modelling with spaCy and scikit-learn](https://www.kaggle.com/code/thebrownviking20/topic-modelling-with-spacy-and-scikit-learn)

[3] [You are what you read: Building a personal internet front-page with spaCy and Prodigy](https://2023.pycon.de/program/NWSLUH/)  -->
