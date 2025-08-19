# Learing-Note
This repo contains personal notes and summaries from my study journey in the Columbia University’s AI for Business course (as an NRA student)

<br><br>
<br><br>



## 3.1 Evaluating ML Systems
When evaluating a Machine Learning model, don’t rely solely on accuracy, especially with skewed datasets. Use the Confusion Matrix values TP, TN, FP, FN — obtained by comparing the model’s predictions with the ground truth on a held-out test set — and apply Precision, Recall, and F1-score formulas for a more reliable performance assessment.
  Accuracy = (TP + TN) / (TP + TN + FP + FN)
  Precision = TP / (TP + FP)
  Recall = TP / (TP + FN)
  F1-score = 2 * (Precision * Recall) / (Precision + Recall)

## 3.2 Python Introduction
 an introduction to Python : an easy-to-learn programming language widely used in Machine Learning due to its clear syntax, extensive libraries, and versatility

## 3.3 Python Datastructures
Lists in Python store ordered data and are accessed by their index, making them ideal for sequences or rankings. Dictionaries store data as key–value pairs, allowing fast lookups based on unique keys. Choosing between them depends on whether you need to access data by position or by a specific identifier.
## 3.4 Python Functions
Functions are reusable blocks of code that can be called from anywhere in a program to perform a specific task.
They help avoid repeating the same code by allowing you to write it once and reuse it with different inputs.
For example, a get_average(scores) function can calculate the average for any class just by passing in that class’s scores.
## 3.5 Python Hash Table
A hash table is a data structure that stores data as key–value pairs, enabling fast lookups (average O(1)) instead of scanning an entire array. Keys should be as unique as possible to avoid duplicates and collisions.
## 3.6 Python Conditionals
Conditional statements let a program make decisions by executing different code blocks depending on whether a Boolean condition is true or false. In Python, this is typically done using if, elif, and else, often combined with logical operators (and, or, not) to form more complex conditions.
## 3.7 Python Loops
This lesson explains the concept of loops in programming, demonstrating how while and for loops work in Python with examples such as printing numbers and calculating the average of a list. Loops allow computers to repeat tasks efficiently and handle large amounts of data without effort.
## 3.8 Python Numpy
This lesson introduces NumPy, a powerful Python library for numerical computing.
np.arange(start, stop, step) creates sequences of numbers (e.g., np.arange(0, 12, 2) → [0, 2, 4, 6, 8, 10]).
reshape() changes the shape of an array without changing its data.
NumPy arrays make operations on large datasets much faster and easier compared to Python lists.
## 3.9 Python Pandas
Learned how to create pandas DataFrames from NumPy arrays, customize column names, and access rows/columns using iloc. Also practiced exploring data with .describe(), .index, and .columns to understand structure and summary statistics.
## 3.10 Python Variables
Variables in Python are identifiers that store values in memory, so you can later retrieve or manipulate them. Defining variables is simple (x = 3, y = 6, z = x + y), and Python infers data types automatically (integers, floats, strings, booleans), unlike strongly typed languages (e.g., Java). We also covered order of operations (parentheses, multiplication/division before addition/subtraction), comments using #, and examples with different variable types and expressions. This makes variables the foundation for writing programs and performing computations.
## 3.11 Getting Dataset
We use Python and ML libraries (NumPy, Pandas, Matplotlib, scikit-learn) to load and preprocess the LFW face dataset, then build a simple Logistic Regression model to recognize individuals in the images.

The process includes importing libraries, loading data, exploring and wrangling it, splitting into train/test sets, training the model, and evaluating its performance.

## 3.12 Using Dataset
The LFW face dataset stores images as numerical pixel values with each person assigned a numeric ID, which can be mapped to their actual name for easy visualization and interpretation.
## 3.13 Building the Model
The pixel values of each LFW image are stored as a 1D array and reshaped into 2D (50×37) for visualization.
The dataset is split into train (80%) and test (20%) sets to train a Logistic Regression model for classifying faces.
The model is then evaluated on unseen test images, and predictions can be visualized alongside the actual images to check accuracy.
## 3.14 Using ML Models to Make Prediction
This facial recognition system uses Logistic Regression to classify who a person is in an image based on labeled training data. Each image is flattened into a 1D vector for the model, and predictions are compared with true labels to evaluate accuracy (~84%). To scale for more people, stronger models like CNNs and feature extraction from images are recommended.


#Lec 3
            no test !
