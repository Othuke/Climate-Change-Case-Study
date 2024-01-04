# Climate-Change-Case-Study

This project is an NLP Classification task. The dataset is obtained from Kaggle.
Many companies are built around lessening one’s environmental impact or carbon footprint. They offer products and services that are environmentally friendly and sustainable, in line with their values and ideals. They would like to determine how people perceive climate change and whether or not they believe it is a real threat. This would add to their market research efforts in gauging how their product/service may be received.

The goal of this project was to create a Machine Learning model that can classify whether or not a person believes in climate change, based on their novel tweet data.

The preprocessing steps include:
* Masking the Twitter handles
* Replacing the URLs with suitable text
* Removal of punctuations, numbers, special characters and whitespace
* Removal of stopwords, converting to lowercase and lemmatization

Some major highlights include:
* The tweet sentiment feature (target variable) was imbalanced and I tried several balancing techniques; upsampling, downsampling and smote. I compared their performance with that of the data without resampling.
* The model was trained with a pipeline containing a vectorizer and a transformer. The model was also evaluated using accuracy, precision, recall and f1 score.
* Several models were evaluated which include - Logistic Regression, Naive Bayes (Gaussian, Multinomial and Bernoulli), Support Vector Machine (Linear, Polynomial and Radial basis function kernels), and XGboost.
* To improve the model, different ensemble methods were used which include bagging, stacking, soft voting and hard voting.

The entire notebook can be accessed [here](https://github.com/Othuke/Climate-Change-Case-Study/blob/main/Climate%20change%20classification.ipynb)
