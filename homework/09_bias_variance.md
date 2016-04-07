## Class 9 Pre-work: Bias-Variance Tradeoff

Read this excellent article, [Understanding the Bias-Variance Tradeoff](http://scott.fortmann-roe.com/docs/BiasVariance.html), and be prepared to **discuss it in class** on Thursday.

**Note:** You can ignore sections 4.2 and 4.3.

Here are some questions to think about while you read:
* In the Party Registration example, what are the features? What is the response? Is this a regression or classification problem?
   - Classification problem
   - Response: Party designation
   - Features: wealth, religiosity

* Conceptually, how is KNN being applied to this problem to make a prediction?
   - the features are used to define a map to describe party designation
   

* How do the four visualizations in section 3 relate to one another? Change the value of K using the slider, and make sure you understand what changed in the visualizations (and why it changed).
   - Fig 3 Training data
   - Fig 4 Test data
   - Fig 5 is the predictive model

* In figures 4 and 5, what do the lighter colors versus the darker colors mean? How is the darkness calculated?
*  probability of being one party or another.  The darker the color the more likily of being that party


* What does the black line in figure 5 represent? What predictions would the best possible machine learning model make, with respect to this line?  The black line is the boundary between the two party labels.  The line would be smooth not jagged but also be representative of the data.  
  

* Choose a very small value of K, and click the button "Generate New Training Data" a number of times. Do you "see" low variance or - - high variance, and low bias or high bias?
- high variance, low bias.

* Repeat this with a very large value of K. Do you "see" low variance or high variance, and low bias or high bias?
-low varience, high bias

* Try using other values of K. What value of K do you think is "best"? How do you define "best"?
- Somewhere between 17 and 22

* Does a small value for K cause "overfitting" or "underfitting"?
- underfitting

* Why should we care about variance at all? Shouldn't we just minimize bias and ignore variance?
- no you can't simply ignore variance because the model will only work in long-run average sense and not for individual predictions.
