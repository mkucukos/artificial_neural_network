# Natural Language Processing

Here I define what type of review is positive and what type of review is negative? First I split the review into its different words so that I can apply stemming to each of these words with stopwords. Stopwords are the most prevalent and repeated words in any language
Then, using the CountVectorizer, I created the Bag of Words model, which converts provided text into a vector based on the frequency (count) of each word that appears in the full text. Then I divided the data into training and test sets, and trained the Naive Bayes, K nearest, and SVM classification models using the Training set. For each model, a single prediction was provided as an example. For the Naive Bayes, K nearest, and SVM classification models, the confusion matrix accuracy is 0.72, 0.64, and 0.72, respectively.

```bash
$ pip install -r requirement.txt
```
![model's output](./Figure1.png)
![model's output](./Figure2.png)
![model's output](./Figure3.png)
