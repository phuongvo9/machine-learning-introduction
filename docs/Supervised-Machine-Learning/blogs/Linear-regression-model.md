**I. Review Supervised Learning definition before Linear Regression**

*   **Definition:** Supervised learning involves training a model using a dataset that includes both input features and their corresponding output targets (or "right answers")
*   **Training Process:**
    *   A training set is fed into a learning algorithm
    *   The algorithm produces a function (f), also called the model
    *   This function (f) takes new input (x) and outputs an estimate or prediction (ŷ or y-hat)

*   **Types of Supervised Learning Models**:
    *   **Regression Models:** Predict numerical outputs (e.g., house prices)
    *   **Classification Models:** Predict categories (e.g., cat vs. dog, disease classification)

**II. Linear Regression**

*   **Definition:** A type of regression model that fits a straight line to data
    *   It is a widely used algorithm and a foundation for understanding more complex models
*   **Goal:** To predict a numerical output (y) based on a single numerical input feature (x) using a linear function
*   **Function Representation:**
    *   The linear function is often expressed as:  **f(x) = wx + b**
    *   **w** and **b** are parameters that determine the slope and y-intercept of the line
    *   The goal of the learning algorithm is to find the optimal values for w and b that fit the training data well.
*   **Univariate Linear Regression:**
    *   Also called linear regression with one variable
    *   Involves a single input feature (x)
*   **Example:** Predicting house price (y) based on the size of the house (x)

**III. Key Concepts and Notation**

*   **Training Set:**  The dataset used to train the model, including inputs and outputs
*   **Input Feature (x):** The variable used to make a prediction (e.g., size of a house)
*   **Output Target (y):** The actual true value that the model is trying to predict (e.g., the actual price of the house in the training set)
*   **Prediction (ŷ):** The estimated value of y, computed by the function f (the model)
*   **Number of Training Examples (m):**  Total number of rows (data points) in the training set
*   **Training Example:** A single pair of input and output (x, y)
*   **Indexed Training Examples (x<sup>(i)</sup>, y<sup>(i)</sup>):** A specific training example in the training set, where i is the index (row number)

**IV. Process of Supervised Learning (Linear Regression)**

1.  **Gather Data:** Collect a training set with input features (x) and corresponding output targets (y)
2.  **Prepare Data:** Organize data in a table, with rows for each training example and columns for input features and output targets
3.  **Choose Model:** Select a model (in this case, a linear regression model), which is the linear function: f(x) = wx + b
4.  **Train the Model:** Feed the training set to the learning algorithm, which will determine the values of parameters w and b that best fit the data
5.  **Make Prediction:** Using the function f, estimate an output (ŷ) for a new input (x)

**V. Cost Function**

*  A cost function is one of the most important concepts in machine learning, including linear regression. However, the specific mechanics of the cost function are not detailed in this discussion
*  The cost function is something that is used to train the model and should be explored further in another discussion

**Mindmap Structure**

*   **Supervised Learning:**
    *   **Linear Regression**
        *   **Definition**
        *   **Function Representation**
        *   **Univariate Type**
    *   **Training Process**
        *   **Data Gathering**
        *   **Data Preparing**
        *   **Model Selection**
        *   **Training**
        *   **Prediction**
    *   **Key Concepts and Notation**
        *   **x, y, ŷ, m**
        *   **Training Set**
        *   **Examples**
        *   **Indexed Examples**
        *   **Universal Conventions**
        *   **Cost Function (not detailed)**
        *   **Relationship to Supervised Learning**
*   **Linear Regression:** Include sub-branches for its definition, function representation (f(x) = wx + b), and univariate type
*   **Training Process:** Include data gathering, preparing, model selection, training, prediction.
*   **Key Concepts and Notation:**  List x, y, ŷ, m, training set, examples, indexed examples, and briefly note they are universal conventions in the field

