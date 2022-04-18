# MIE424 - Final Project
Type of project: A. Implementation

Title: Comparing SVM and Softmax Activation Functions on Applications of Image Recognition and Sentiment Analysis

Members: Maria Papadimitriou, Margaret Tkatchenko, John Volpatti, Hilary Wang

Most relevant papers from literature: 

Y. Tang, “Deep learning using linear support vector machines,” arXiv, 21-Feb-2015. [Online]. Available: https://arxiv.org/pdf/1306.0239.pdf. [Accessed: 18-Apr-2022].

Y. Kim, “Convolutional neural networks for sentence classification,” arXiv.org, 03-Sep-2014. [Online]. Available: https://arxiv.org/abs/1408.5882. [Accessed: 18-Apr-2022].

# Python Files and Code Used from Other Repos

sentiment-analysis-cnn-svm.ipynb: adapted from https://github.com/AFAgarap/cnn-svm

image-recognition-cnn-svm.ipynb: adapted from https://github.com/bentrevett/pytorch-sentiment-analysis/blob/master/4%20-%20Convolutional%20Sentiment%20Analysis.ipynb

[CNN SVM sent. Anal.py]: our own program; using methodologies and parts of code from the two previous files. 

# Setup and Run

The notebook files are recommended to be run through Google Colab as this is where the code was developed and tested. 

Our notebook files do not rely upon files of data; instead, the data is available through pytorch or tensorflow packages. 

Once a notebook is downloaded and uploaded to Google Colab, the code can be run by either running one cell at a time or by running all.

# Project description

The use of CNNs has traditionally focused on image data, however, they also perform remarkably well in other areas including NLP. As the structure and parameters of a CNN lead to varying levels of performance, this report aims to evaluate a deep learning model using a Linear SVM to the task of sentiment analysis. We implemented a CNN with an SVM top layer (first introduced by Tang to the problem of image recognition), and compared results to a CNN with softmax activation function in the final layer. After training on the Large Movie Review Dataset from Stanford University, the CNN-SVM model was able to achieve higher testing accuracy than the CNN with softmax activation.
