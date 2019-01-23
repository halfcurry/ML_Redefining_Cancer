# Personalized Medicine: Redefining Cancer Treatment 

Machine Learning Course Project attempting the completed [Kaggle Challenge](https://www.kaggle.com/c/msk-redefining-cancer-treatment) of the same name.
Used NLP and ML techniques to classify genetic mutations from manually annotated Biomedical text.

In this project, we have an expert-annotated
knowledge base where world-class researchers and
oncologists have manually annotated thousands of
mutations in genes. These mutations have been
classified into 9 classes. Our goal is to find a
machine learning algorithm that, when given the text,
automatically classifies these genetic variations.

A cancer tumor can have thousands of genetic
mutations. But the challenge is distinguishing the
mutations that contribute to tumor growth (drivers)
from the neutral mutations (passengers). This
interpretation of genetic mutations is being done
manually, which is a very time-consuming task where
a clinical pathologist has to manually review and
classify every single genetic mutation based on
evidence from text-based clinical literature. Hence,
we are motivated to use machine learning and
natural language processing techniques in order to
automatically classifies these genetic variations.

This is a recently completed [Kaggle challenge](https://www.kaggle.com/c/msk-redefining-cancer-treatment). The
best observed scores (in multi-class log loss) for the
public leaderboard section, which uses 76% of the test
data, can be treated as the state-of-the-art results
obtained so far on the given dataset. The best results
achieved is around 0.11 and 2.03 on the private
leaderboard.

The best performance achieved was that of Random Forest with the Word2Vec model.
The performance of Doc2Vec was very similar to this.
Using Neural Networks performed poorer compared to
random forest with larger log loss. Upsampling did give
better results when optimised and good validation
score but with test set at Kaggle it performed poorly.

Refer to the report or slides for more information. 
