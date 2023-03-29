---
title: "Module 21 Challenge"
---

<div id="bootcamp"><img style="display: none;" src="https://static.bc-edx.com/data/dl-1-2/m21/lms/img/banner.jpg" alt="lesson banner" />

### Background

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:



1. **Overview** of the analysis: Explain the purpose of this analysis.
The purpose of this analysis is to evaluate the models created and the efficacy of the adjustments made in an attempt to achieve the target of a high accuracy

2. **Results**: Using bulleted lists and images to support your answers, address the following questions:

  * Data Preprocessing
    * What variable(s) are the target(s) for your model?
	The target of the model is whether or not a loan was successful using the "IS_SUCCESSFUL" value.
    * What variable(s) are the features for your model?
	Application Type, Affiliation, Classification, Use Case, Status, Income Amount, Special Considerations, and Ask Amount were the features
    * What variable(s) should be removed from the input data because they are neither targets nor features?
	EIN and Name were removed

* Compiling, Training, and Evaluating the Model
    * How many neurons, layers, and activation functions did you select for your neural network model, and why?
	I used 3 layers. 24 neurons in the first layer, 16 in the second, and 16 in the third. The relu activation function was used.
    * Were you able to achieve the target model performance?
	I was not
    * What steps did you take in your attempts to increase model performance?
	I removed the status and special considerations columns and increased the threshholds in bucketing in an attempt to reduce the noise that may adversely effect the model during training.

3. **Summary**: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
Both models failed to achieve the target accuracy of 75%, though the refined model did have a final accuracy increase of .2%
