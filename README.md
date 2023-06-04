# Topic Modeling of [PyConDe & PyData Berlin 2023](https://2023.pycon.de/) Sessions 



![](1.png)
![](2.png)
![](3.png)
![](4.png)


As a first-time attendee of such a great conference, I would say I am so lucky to get the grant provided by the Diversity Committee. It made it possible for me to attend this event and gain valuable insights into the latest trends and innovations in the field and make connection to over 1200 people with same interets. That's amazing!

After back from the event, I think why not using the new things you learned from the conference to make a summary of it. I am going to use spaCy to do topic modelling for all the session in PyConDe & PyData Berlin 2023.

### Preparation
The pakages I need:
```
!pip install pyLDAvis -qq
!pip install -qq -U gensim
!pip install spacy -qq
!pip install matplotlib -qq
!pip install seaborn -qq
!python -m spacy download en_core_web_md -qq
```

Topic modeling is an unsupervised machine learning technique that extract hidden topics from text. The algorithm I am going to use is LDA.

Step 1 get the data - done

Step 2 tokenization 

Step 3

Step 4 Candidate topics

Step 5 Topic distribution

[Github code](pyconde_analysis.ipynb)

### References
[1] [](https://towardsdatascience.com/topic-modelling-in-python-with-spacy-and-gensim-dc8f7748bdbf)

[2] https://www.kaggle.com/code/thebrownviking20/topic-modelling-with-spacy-and-scikit-learn
