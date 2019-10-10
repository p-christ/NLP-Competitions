# NLP-Tasks

![BERT](https://i2.wp.com/mlexplained.com/wp-content/uploads/2019/01/bert.png?fit=400%2C400&ssl=1)

![TF2.0](https://cdn-images-1.medium.com/max/1024/1*-QTg-_71YF0SVshMEaKZ_g.png)

This repository provides simple notebooks that achieve high scores (~top 1%) in various NLP competitions using TensorFlow 2.0. All notebooks
can be run on Google colab in under 1 hour. 

## 1. Offensive Language Classification ([Codalab](https://competitions.codalab.org/competitions/20011))
We fine-tune a pre-trained BERT model to achieve scores that would have won the competition. See `notebooks/Codalab_Offensive_Language_Competition_ipynb`

## 2. Toxic Comment Classification ([Kaggle](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/rules))
We implement a simple model for this task using Glove word embeddings and a bidirectional GRU that achieve a score 
 that would have put us roughly in the top 1\% of Kaggle submissions for this competition. See `notebooks/Toxic_Comment_Classification_(Kaggle)_Simple_Baseline.ipynb` 
