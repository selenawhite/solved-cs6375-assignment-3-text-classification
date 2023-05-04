Download Link: https://assignmentchef.com/product/solved-cs6375-assignment-3-text-classification
<br>
<strong> </strong><strong>Naive Bayes and Logistic Regression for Text Classification </strong>

In this homework you will implement and evaluate Naive Bayes and Logistic Regression for text classification. Use Python to implement your algorithms.

Download the spam/ham (ham is not spam) dataset available on the elearning. The data set is divided into two sets: training set and test set. The dataset was used in the Metsis et al. paper [1]. Each set has two directories: spam and ham. All files in the spam folders are spam messages and all files in the ham folder are legitimate (non spam) messages.

Implement the multinomial Naive Bayes algorithm for text classification described here: <a href="http://nlp.stanford.edu/IR-book/pdf/13bayes.pdf">http://nlp.stanford.edu/IR-book/pdf/13bayes.pdf</a> (see Figure 13.2). Note that the algorithm uses add-one Laplace smoothing. Make sure that you do all the calculations in log-scale to avoid underflow. Use your algorithm to learn from the training set and report accuracy on the test set.




Implement the MCAP Logistic Regression algorithm with L2 regularization that we discussed in class (see Mitchell’s new book chapter). Try different values of λ. Use your algorithm to learn from the training set and report accuracy on the test set for different values of λ. Use gradient ascent for learning the weights. Do not run gradient ascent until convergence; you should put a suitable hard limit on the number of iterations.




Improve your Naive Bayes and Logistic Regression algorithms by throwing away (i.e., filtering out) stop words such as the” of” and for” from all the documents. A list of stop words can be found here: <a href="https://www.ranks.nl/stopwords">https://www.ranks.nl/stopwords</a><a href="https://www.ranks.nl/stopwords">.</a> Report accuracy for both Naïve Bayes and Logistic Regression for this filtered set. Does the accuracy improve? Explain why the accuracy improves or why it does not?

References

[1] V. Metsis, I. Androutsopoulos and G. Paliouras, Spam Filtering with Naive

Bayes – Which Naive Bayes?”. Proceedings of the 3rd Conference on Email and Anti-Spam (CEAS 2006), Mountain View, CA, USA, 2006.


