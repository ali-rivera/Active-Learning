# kNN on a Board

## Summary of Learning Objectives

**Learning Objectives:**
<br /> *Learning Objective 1:* Students will be able to explain the process of a kNN alogirthm for classification.
<br /> *Learning Objective 2:* Students will be able to evaluate k values to choose the optimal value and justify their choice with evidence.
<br /> *Learning Objective 3:* Students will be able to visualize how hyperparameter choice is represented in 2-dimensional space.

## Pre-reading 
- [Machine Learning with Python for Everyone by Mark Fenner, section 3.5 Simple Classifier #1: Nearest Neighbors, Long Distance Relationships, and Assumptions](https://learning.oreilly.com/library/view/machine-learning-with/9780134845708/ch03.xhtml#ch03lev1sec5)
- Student Instructions

## Active Learning session materials

### Student Instructions

**General Description:** In this lab we will explore the kNN algorithm using a visual representation of purchasing data from Kaggle. The data contains social network user information including estimated salary and age, and whether the user bought a product. We will use the kNN algorithm to predict if a new user is likely to purchase a product using their salary and age. 

**Why am I doing this?**  kNN is a common algorithm used for classification problems. This lab will allow you to work through the algorithm in the same way that the computer does (just on a smaller scale) and give you a hands-on understanding of how classifications are made in the model. 

**What am I going to do?** Using the kNN board, you will first identify the 5 points in black. Then, you will classify these points as one of two classes: purchased - blue or not purchased - orange. Choose 3 k values (must be greater than 1 and odd), find the k nearest neighboring points using Euclidean distance – a straight line between 2 points and classify the point as purchased or not purchased. Record the classification for each point in a table. Then, compare these results to the actual class (obtained from your TA) to pick the best k value and answer the questions below. 

### Board 
```{figure} kNN_output.png
:name: kNN-board

Board students will use in the activity. See {ref}`Instructor Notes` below for details.
```

### Instructor Notes
This activity assumes that students have prior knowledge of the following terms in the context of data science: 
- algorithmic thinking
- classification models
- training vs. test data
- evaluation criteria
- overfitting vs. underfitting

#### True Values
Point A: Purchased (Blue)
<br /> Point B: Not Purchased (Orange)
<br /> Point C: Not Purchased (Orange)
<br /> Point D: Purchased (Blue)
<br /> Point E: Purchased (Blue)

#### Recommended Materials

It is recommended that this activity be done "off-line" and therefore requires some materials. The {ref}`kNN board <kNN-board>` above can be printed in many different formats, but for sustainability of resources it is recommended that the image be printed as large as 24" x 36" and lamintated.

- printed kNN Board 
- dry eraser markers (or some other erasable writing utensil)
- rulers

Students use dry erase markers and rulers to aid in chosing and keeping track of the negihbors as they classify each of the test points.

## Assessment

**Questions**

1. Using what you learned in class about kNN, explain in your own words (at a "rubber duck level") how the kNN model works. Be sure to answer the following questions in your explanation: 
<br /> &emsp; a. What does k represent? 
<br /> &emsp; b. How is a prediction made for a new observation (one not in the training data set)? 
<br /> &emsp; c. In this example, is kNN being used for classification or regression? Why? 
<br /> &emsp; d. Include references (links are fine) to any additional sources you use - you may find this [IBM article](https://www.ibm.com/topics/knn) helpful. 

2. Include the table you recorded your classifications in for all 3 k values you tested for each of the 5 test points. 

3. Recommend a value for k based on your observations. Provide a rationale for why you chose that value. 

4. Using the k value you have chosen, create estimated boundaries areas (like the example in {ref}`the example below <boundarylines-example>`). Include a picture of the board with the drawn boundaries. 

5. Which areas of the graph did kNN do best in? Worst? Why do you think this is? 

6. Overfitting and underfitting are common issues in machine learning. Explain why picking a k value too small overfits your model, and a k value too large underfits your model. 

```{figure} image.png
:name: boundarylines-example

Example of boundary lines mapped onto space for k=1 & k=15
```


## Evaluation rubric

**How will I know I have succeeded?**
| **Specs Category** | **Specs Details** |
|----------------|---------------|
| **Formatting**     | - 2 pages max <br /> - PDF format <br /> - Headings <br /> &emsp; - Lab Name <br /> &emsp; - Your name, course, date <br /> &emsp; -Questions  |
| **Questions**      | - Goal: Explore the kNN algorithm through the guided questions <br /> - Detailed responses to the questions that include examples from your experience where appropriate <br /> - Completed table for your 3 k values <br /> - Image of the graph with your drawn boundary lines <br /> - Format your responses in a numerical list corresponding to the questions list  |

**Acknowledgements:** Special thanks to Jess Taggart from UVA CTE for coaching us. This structure is pulled directly from [Streifer & Palmer (2020)](https://cte.virginia.edu/blog/2020/12/04/alternative-grading-practices-support-both-equity-and-learning). 