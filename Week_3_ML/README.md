# Week 3 | Machine Learning

## Introduction 

Even though ML doesn't actually need an introduction in today's world, where millions of people research in this field, and where every other day there's a new *state of the art* techinique. Machine Learning is basically automating and improving the learning process of computers based on their experiences without being actually programmed i.e. *without* any human assistance.   

In **Traditional Programming**, We feed in Data (*Input*) + Program (*Logic*), run it on machine and get output.

While in **Machine Learning**, We feed in Data (*Input*) + *Output*, run it on machine during training and the machine creates its own program(*Logic*), which can be evaluated while testing.

Excited? Now go on, begin your journey into this vast and the most buzzing field in Computer Science here.

## Resources

- ### [Machine Learning](https://www.wncc-iitb.org/wiki/index.php/Machine_Learning) 
   
   *This is for those who have some coding experience, but never done Machine Learning before. If you feel your concepts about Python or programming in general are shaky, first complete our tutorial on [**Python**](https://github.com/wncc/CodeInQuarantine/tree/master/Week_1_Python). Even if you have completed the much renowned **AndrewNG** [Machine Learning](https://www.coursera.org/learn/machine-learning) course, go through this article, because here we implement every algorithm in Python instead of MATLAB.*

- ### [Deep Learning](https://www.wncc-iitb.org/wiki/index.php/Deep_Learning)
  
  *Only **after** you have gone through and implemented the algorithms in the above article should you continue with this one. It introduces you to all the important concepts and applications of **Neural Networks***

## Tasks

### 1. Stanford CS231n Assignments

Stanford runs an amazing course [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/) whose assignments serve as a perfect way to practice and strengthen your concepts.

- The [First Assignment](https://cs231n.github.io/assignments2019/assignment1/) makes you implement *kNN*, *SVM*, *Softmax*, and a simple *Neural Network* without any ML libraries.

- The [Second Assignment](https://cs231n.github.io/assignments2019/assignment2/) helps you get acquainted with *Backpropogation*, *Batch Normalisation*,*Dropout*, *CNNs*, and *deep learning frameworks*.

- The [Third Assignment](https://cs231n.github.io/assignments2019/assignment3/) is where you'll implement *RNNs*, *LSTMs*, and *GANs*  

_You should definitely checkout their excellent [Notes](https://cs231n.github.io/) and [Video Lectures](https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv) if you are stuck somewhere, or have difficulties in understanding some particular concepts._

### 2. Document Classification 

Document classification is an example of Machine Learning (ML) in the form of Natural Language Processing (NLP). This is especially useful for publishers, news sites, blogs or anyone who deals with a lot of content. 
Through this assignment, we will try to implement different clustering algorithms to classify documents from the real-world [BBC Dataset](https://www.kaggle.com/shivamkushwaha/bbc-full-text-document-classification).

#### Data Preprocessing:
- Download the [__BBC Dataset__](https://www.kaggle.com/shivamkushwaha/bbc-full-text-document-classification) [~ 5 MB] which consists of 2225 documents from the BBC news website corresponding to stories in __5 topical areas__ (business, entertainment, politics, sport, tech) from 2004-2005.
- Write a function that reads all the `*.txt` files present in each of the 5 topical folders, [normalize the text](https://programminghistorian.org/en/lessons/normalizing-data) for each document & create a dataframe (use `pandas`) with headers similar to:

  | sr_no | doc_text | class |
  |--|--| -- |
  | 1 | Ad sales boost time ...  that stake. | business |
  | ... | ... | ... |

- Now, we can create feature vectors for each of these documents & append them as corresponding columns to the above dataframe. Try to experiment with the following models to create feature vectors:
  - [Bag of Words Model](https://www.geeksforgeeks.org/bag-of-words-bow-model-in-nlp/)
  - [TF-IDF Model](https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76)
  - Any other that you may find interesting

  You can choose to implement these from scratch or use existing implementations from `sklearn`.

  The dataframe should now look like:
  | sr_no | doc_text | class | bow_vectors | tfidf_vectors |
  |--|--| -- | -- | -- |
  | 1 | ad sales boost time ...  that stake | business | {"ad": 1, ...} | {"ad": 1, ...}
  | ... | ... | ... | .. | .. |

- Shuffle the rows of this dataframe & split it into a training, validation & test set. You could choose splits such as 70 : 10 : 20 [training : validation : test]

#### Training the Classifier

You can now implement the following algorithms for the document classification task:
- K-Means Clustering
- KNN Clustering
- Gaussian Mixture Model (GMM)

You can try to work with different distance formulations like [Cosine Distance](https://en.wikipedia.org/wiki/Cosine_similarity), [Euclidean Distance](https://en.wikipedia.org/wiki/Euclidean_distance), [Manhattan Distance](https://xlinux.nist.gov/dads/HTML/manhattanDistance.html), [Chebyshev Distance](https://en.wikipedia.org/wiki/Chebyshev_distance), etc.

You can use techniques such as K-Fold Cross-Validation to check for over-fitting of the model.

Once trained, test your model on the 'test' split.


### 3. Kaggle Contests

[Kaggle](https://www.kaggle.com/) is a platform for predictive modelling and analytics competitions in which companies and researchers post data and statisticians and data miners compete to produce the best models for predicting and describing the data.

Following are a list of some contests that you can take part in by creating ML/DL Models:

- [Dog Breed Identification Challenge](https://www.kaggle.com/c/dog-breed-identification/data)
- [Mushroom Classification](https://www.kaggle.com/uciml/mushroom-classification)
- [Hand Gesture Recognition](https://www.kaggle.com/sprakash08/hand-gestures-recognition)
- [FIFA 2019 Players' Wages](https://www.kaggle.com/c/fifa2019wages/data)
- [Elo Merchant Category Recommendation Challenge](https://www.kaggle.com/c/elo-merchant-category-recommendation)

You can try any preprocessing methods, algorithms & ensembles for these challenges. Augmented deep Learning architectures such as CNNs, Autoencoders & RNNs could come in handy while attempting these challenges.


### 4. Denoising an image


Go to [denoising-task](./denoising-task) to find the problem statement and relevant data.
You don’t need to know about *Markov Random Fields* (MRF) priors for attempting this task. The following information is sufficient, though slides for MRF priors and image denoising are present if you wish to learn more:

For each of the `g()` function :

- Minimise the following function (by gradient descent) to get the denoised image :    
&Sigma;{a*(y<sub>i</sub>-x<sub>i</sub>)<sup>2</sup> + g(x<sub>i</sub>-x<sub>i1</sub>)+g(x<sub>i</sub>-x<sub>i2</sub>)+g(x<sub>i</sub>-x<sub>i3</sub>)+g(x<sub>i</sub>-x<sub>i4</sub>) }
where i<sub>1</sub>, i<sub>2</sub>, i<sub>3</sub>, i<sub>4</sub> are the 4 neighbouring pixels of i. `y` is the noisy image and `x` is the denoised image.

- The role of `g()` is of *edge preservation* (neighbouring values of pixels shouldn’t differ by much , and should differ by much only at edges)
, the role of **(y<sub>i</sub>-x<sub>i</sub>)<sup>2</sup>** is *noise removal*. While `a` is for giving weights to noise removal and edge preservation