## Building a Spam Filter with Naive Bayes

### About:

Goal of this project is to create a spam filter that classifies new messages with an accuracy greater than 80% — so we expect that more than 80% of the new messages will be classified correctly as spam or ham (non-spam).

To train the computer  to classify messages, we'll use the multinomial Naive Bayes algorithm along with a dataset of 5,572 SMS messages that are already classified by humans. The dataset was put together by Tiago A. Almeida and José María Gómez Hidalgo, and it can be downloaded from [the The UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection). You can also download the dataset directly from this [link](https://dq-content.s3.amazonaws.com/433/SMSSpamCollection). The data collection process is described in more details on [this page](http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/#composition), where you can also find some of the authors' papers.

### Steps:

  * Assign probabilities to events based on certain conditions by using conditional probability rules.
  * Assign probabilities to events based on whether they are in relationship of statistical independence or not with other events.
  * Assign probabilities to events based on prior knowledge by using Bayes' theorem.
  * Create a spam filter for SMS messages using the multinomial Naive Bayes algorithm.
  * Classifying A New Message and Measuring the Spam Filter's Accuracy

### Built With :

  * Python 3
  * Jupyter Notebook