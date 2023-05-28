# SPAM CLASSIFICATION

This repository contains a simple spam classification project using the Naive Bayes algorithm. The project aims to classify text messages as spam or ham (non-spam). The dataset used is the [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection) from the UCI Machine Learning Repository.

## Data Exploration

The dataset is explored by performing text cleaning, removing duplicates, and analyzing the data.

### Data Visualization

- Pie chart: Visualizes the distribution of spam and ham messages.
- Bar chart: Illustrates the count of spam and ham messages.
- Word cloud: Displays a word cloud representation of spam and ham messages.

## Tokenization

Tokenization is performed to break the text into sentences, words, and characters.

- Sentence tokenization: Splits the text into sentences.
- Word tokenization: Divides the text into individual words.
- Character tokenization: Breaks the text into individual characters.

### Description of Ham and Spam

The ham and spam categories are described, providing insights into their characteristics and composition.

## Using Pretrained Classifiers

Several pretrained classifiers are employed to classify the spam messages.

| Model Name                 | Accuracy  | Time Taken |
| -------------------------- | --------- | ---------- |
| AdaBoostClassifier         | 96.611810 | 0.696584   |
| BaggingClassifier          | 95.934172 | 1.062076   |
| BernoulliNB                | 97.386254 | 0.012100   |
| CalibratedClassifierCV     | 98.644724 | 0.177198   |
| ComplementNB               | 96.515005 | 0.010757   |
| DecisionTreeClassifier     | 95.643756 | 0.131743   |
| DummyClassifier            | 88.770571 | 0.001799   |
| ExtraTreeClassifier        | 96.127783 | 0.017295   |
| ExtraTreesClassifier       | 98.160697 | 1.323269   |
| GradientBoostingClassifier | 96.708616 | 1.091855   |
| KNeighborsClassifier       | 92.545983 | 0.173880   |
| LogisticRegression         | 97.676670 | 0.058000   |
| LogisticRegressionCV       | 98.451113 | 2.000187   |
| MLPClassifier              | 98.063892 | 32.597064  |
| MultinomialNB              | 98.160697 | 0.040769   |
| RandomForestClassifier     | 97.386254 | 1.374330   |
| SGDClassifier              | 97.773475 | 0.009635   |
| SVC                        | 97.483059 | 1.680027   |

## Bag of Word with LSTM

Accuracy score: 0.9796708615682478

## Bag of Word with MLP

Accuracy score: 0.9864472410454985

## FastText Embedding with LSTM

Accuracy score: 0.9002904162633107

## FastText Embedding with MLP

Accuracy score: 0.8993223620522749

Please note that this project was developed by a college student during late-night hours, and the code might not be extensively documented. However, feel free to explore and modify the code as per your requirements. If you encounter any issues or have suggestions for improvement, please submit an issue.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please feel free to submit a pull request with your proposed changes.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

Enjoy exploring the spam classification project and have a great time!
