# Coursera-Advanced-Machine-Learning
The goal of setting up this repo is to make full use of Coursera Advanced Machine Learning Specialization.

### Main Features
This repo mainly provides the following features:
1. For review purpose : A more convenient visualization of jupyter notebooks without setting up notebook server locally.
2. The references of papers which appear in the courses as well as some notes about the papers
3. Nicely commented code from helper functions to project architecture as well as a guideline of how to go through them
4. Extend the project to end to end system: from data labeling to research diary (Ongoing)

Recourse collection contributors: [Michael Wang](https://github.com/MichaelYxWang)


### Beyond the assignments
I want to fully utilize all the projects in this specialization. However, since each project will focus on a specific course topic, not all of them have a standard procedure. I believe that setting up standard procedures for different ML/DL problems will speed up research and development. Therefore, for each of the course project, I set up a seperate jupyter notebook to faciliate my research diary which has the following stucture:


**2. Data Aquisition**
- The goal is to make full use of gpu on Google Colab or Kaggle Kernel, so it is very important to retrive data and put it in corresponding folders. A setup script is at required at the start at each notebook for easy data aquisition.

**2. What does raw data look like?**
- Maybe our raw data is completely unreadable from human's perspective. But I think it is always desirable to get an intuition of how these data distributes and looks like. Maybe some plottings.

**3. Data preprocessing to get X_train, y_train (supervised only), etc...**
- Preprocessing should be seperated from model related staff. The seperation will make the debugging easier.

**4. VISUALIZE THE DATA just before they go to the model! (Super Important!)**
- For example, plot images and corresponding labels before going to the training stage!

**5. Postprocessing**
- data normalization, multi-crops...

**6. Model Building**
- Check if non-linear activations, regularization, flatten layer, last softmax etc.. are properly arranged

**7. Model Training**
- Learn and apply different callback funtions
- Learn and apply different metrics (especially for the multi-label case)
- Save every model or save best model

**8. Training Stats Reporting Dashboard**
- Train / Val Curves
- Metrics display

**9. Model Evaluation**
- Evaluation Metrics Report
- FORWARD PASS ON ORIGINAL DATA (end2end, including of processing steps)



### Paper References
#### Course 6 Week 1 :
**[1]** [Syntactic Parsing](https://web.stanford.edu/~jurafsky/slp3/11.pdf)

**[2]** [An Adversarial Review of “Adversarial Generation of Natural Language](https://medium.com/@yoav.goldberg/an-adversarial-review-of-adversarial-generation-of-natural-language-409ac3378bd7)

**[3]** [Graph-powered Machine Learning at Google](https://ai.googleblog.com/2016/10/graph-powered-machine-learning-at-google.html)

**[4]** "Linguistic Knowledge as Memory for Recurrent Neural Networks"[[pdf]](https://arxiv.org/pdf/1703.02620.pdf)

**[5]** "Recursive Deep Models for Semantic Compositionality
Over a Sentiment Treebank"[[pdf]](https://nlp.stanford.edu/~socherr/EMNLP2013_RNTN.pdf)

**[6]** "Learning document embeddings by predicting n-grams for sentiment classification of long movie reviews"[[pdf]](https://arxiv.org/pdf/1512.08183.pdf)

**[7]** "Feature Hashing for Large Scale Multitask Learning"[[pdf]](https://arxiv.org/pdf/0902.2206.pdf)

**[8]** "A Reliable Effective Terascale Linear Learning System"[[pdf]](https://arxiv.org/pdf/1110.4198.pdf)

**[9]** [Vowpal Wabbit](https://github.com/VowpalWabbit/vowpal_wabbit/wiki)

**[10]** "Convolutional Neural Networks for Sentence Classification"[[pdf]](https://arxiv.org/pdf/1408.5882.pdf)

**[11]** "Natural Language Processing (Almost) from Scratch"[[pdf]](http://www.jmlr.org/papers/volume12/collobert11a/collobert11a.pdf)

**[12]** "Character-level Convolutional Networks for Text
Classification∗"[[pdf]](https://arxiv.org/pdf/1509.01626.pdf)
