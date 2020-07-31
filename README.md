# Digit-Recognizer
Kaggle project

Learn computer vision fundamentals with the famous MNIST data

Competition Description
MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

In this competition, my goal is to correctly identify digits from a dataset of tens of thousands of handwritten images.  We are encouraged to experiment with different algorithms to learn first-hand what works well and how techniques compare.

## Table of Contents
<details open>
<summary>Show/Hide</summary>
<br>

1. [ File Descriptions ](#File_Description)
2. [ Technologies Used ](#Technologies_Used)    
3. [ Structure ](#Structure)
4. [ Future Development ](#Executive_Summary)
</details>

## File Descriptions
<details>
<a name="File_Description"></a>
<summary>Show/Hide</summary>
<br>
  
* train.csv  - The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.

Each pixel column in the training set has a name like pixelx, where x is an integer between 0 and 783, inclusive. To locate this pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27, inclusive. Then pixelx is located on row i and column j of a 28 x 28 matrix, (indexing by zero).

For example, pixel31 indicates the pixel that is in the fourth column from the left, and the second row from the top.

* test.csv - the test set, it's the same as the training set, except that it does not contain the "label" column.

* sample_submission.csv - The submission file should be in the following format: For each of the 28000 images in the test set, output a single line containing the ImageId and the digit you predict. For example, if you predict that the first image is of a 3, the second image is of a 7, and the third image is of a 8, then your submission file would look like:

ImageId,Label
1,3
2,7
3,8 
(27997 more lines)

The evaluation metric for this contest is the categorization accuracy, or the proportion of test images that are correctly classified. For example, a categorization accuracy of 0.97 indicates that you have correctly classified all but 3% of the images.

</details>

## Technologies Used:
<details>
<a name="Technologies_Used"></a>
<summary>Show/Hide</summary>
<br>
    
* <strong>Python</strong>
* <strong>Pandas</strong>
* <strong>Numpy</strong>
* <strong>Matplotlib</strong>
* <strong>Scikit-Learn</strong>
* <strong>Keras</strong>
* <strong>Tensorflow</strong>
</details>

## Structure of Notebooks:
<details>
<a name="Structure"></a>
<summary>Show/Hide</summary>
<br>
  
1. Import packages
2. Load data
3. Preprocessing the digit images
4. Data Viz
5. Designing Neural Network Architecture
6. Compile network
7. A quick look at our model's performance
8. Submitting our first Predictions to Kaggle
9. Adding Batch Normalization
10. Submitting our second Predictions to Kaggle
11. Data augmentation
12. Submitting our third Predictions to Kaggle
    
</details>  


<a name="Executive_Summary"></a>
## Future Development
    
* I obtained a very nice socre but maybe later I'd try harder and explore things more deeply. We shall see. I will also maybe consider to deploy my model on internet.



