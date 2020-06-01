# Digit-Recognizer
Recognizing Digits with CNN, participated in Kaggle Competition got score 0.9997 with 86th rank

## About the Data
### Training Data
- The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine.
-Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. 
- Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. 
- This pixel-value is an integer between 0 and 255, inclusive.
- The training data set, (train.csv), has 785 columns. 
- The first column, called "label", is the digit that was drawn by the user. 
- The rest of the columns contain the pixel-values of the associated image.

### Test Data
- The test data set, (test.csv), is the same as the training set, except that it does not contain the "label" column.

## About the Competition
MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

In this competition, our goal is to correctly identify digits from a dataset of tens of thousands of handwritten images. The competion was hosted on kaggle here :- https://www.kaggle.com/c/digit-recognizer/overview
