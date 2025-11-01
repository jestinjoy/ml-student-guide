## **Types of Machine Learning**

Machine Learning can be divided into four main types based on the nature of the data and the way the system learns from it. These are:

1. Supervised Learning
2. Unsupervised Learning
3. Semi-Supervised Learning
4. Reinforcement Learning

Each type follows a different learning approach.

A model in Machine Learning is the mathematical or logical representation of a real-world process that has been learned from data. It is the result of the training process, where an algorithm studies patterns in the data and captures the relationship between input and output variables.

In simple words, a model is what the computer "learns" from the data so that it can make predictions or decisions on new data.

### **Supervised Learning**

Supervised Learning is a type of Machine Learning in which the model learns from labelled data.
Labelled data means that both the input and the correct output are already known.
The algorithm studies the relationship between input and output and learns to predict the output for new inputs.

In Supervised Learning, a training dataset is given to the model. This dataset contains pairs of **input attributes (features)** and **expected outputs (labels or target values)**. The algorithm analyses these pairs and builds a model that represents the relationship between them. After training, the model can take new input data and **predict the output** based on what it has learned.

For example, a model trained on student study hours and their marks can predict the marks of a new student based on how many hours they studied.

#### **Mathematical Definition**

Supervised Learning can be expressed mathematically as finding a function that maps inputs to outputs.

$$
f:X \rightarrow Y
$$

Here,

- $X$ represents the input variables (features),
- $Y$ represents the output variable (label or target),
- $f$ is the function learned by the algorithm.

The goal of the learning process is to find the best possible function $f$ such that:

$$
Y=f(X)
$$

#### **Types of Supervised Learning**

Supervised Learning problems are mainly classified into two types:

1. Classification
2. Regression

##### **Classification**
Classification is a type of Supervised Learning where the output variable has predefined categories or labels. The goal is to assign new inputs to one of these fixed classes.

Examples include

- Predicting whether an email is spam or not spam.
- Identifying if a tumour is benign or malignant.
- Recognizing handwritten digits (0–9).

In classification, the output values are discrete. For instance, an email can belong only to one of the categories - spam or not spam. The model learns decision boundaries that separate different classes based on input features.

Some common classification algorithms are

- Decision Tree - Uses a tree-like structure where decisions are made at each node based on feature values. They are easy to understand and interpret.
- Naive Bayes Classifier - Based on Bayes’ theorem and the concept of probability. It works well for text classification, such as spam detection.
- K-Nearest Neighbours (KNN) - Classifies a new sample based on the majority class of its k nearest neighbours in the dataset.
- Support Vector Machine (SVM) - Finds an optimal boundary (called a **hyperplane**) that separates different classes in the data. Works well for both linear and non-linear classification problems.

Classification algorithms can also be divided based on how they learn and make predictions:

1. Lazy Learners - They do not build a model during training. They store the training data and make predictions only when a new query comes. Example: K-Nearest Neighbours (KNN).
2. Eager Learners - Build a general model during training and use it to make predictions quickly for new data. Example: Decision Tree, Naive Bayes, SVM.

##### **Regression**

Regression is a type of Supervised Learning used when the output variable is **continuous** rather than categorical. The goal is to predict a numerical value based on input data.

Examples include

- Predicting house prices based on location, size, and number of rooms.
- Estimating rainfall based on temperature and humidity data.
- Predicting stock prices.

In regression, the algorithm tries to find the best-fit line or curve that represents the relationship between input and output. The predicted value can take any number within a range, not just fixed categories. Common regression algorithms include

- Linear Regression - Establishes a linear relationship between input and output. Example: Predicting marks based on study hours.
- Polynomial Regression - Models non-linear relationships by fitting a polynomial curve to the data.