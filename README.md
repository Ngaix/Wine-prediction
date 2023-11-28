# Wine-prediction
Analyze and predict wine quality with 2 types of red and white

Description

Wine Quality

Source:

Paulo Cortez, University of Minho, Guimarães, Portugal, http://www3.dsi.uminho.pt/pcortez

A. Cerdeira, F. Almeida, T. Matos and J. Reis, Viticulture Commission of the Vinho Verde Region(CVRVV), Porto, Portugal

@2009

# Evaluation

The evaluation metric for this competition is RMSE.

Submission Format

For every author in the dataset, submission files should contain two columns: id and quality. should be a comma-delimited list.

# Data Set Information:
The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult: Web Link or the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.

# Attribute Information:
For more information, read [Cortez et al., 2009]. Input variables (based on physicochemical tests):

1 - fixed acidity

2 - volatile acidity

3 - citric acid

4 - residual sugar

5 - chlorides

6 - free sulfur dioxide

7 - total sulfur dioxide

8 - density

9 - pH

10 - sulphates

11 - alcohol

12 - type: white or red

Output variable (based on sensory data):

13 - quality (score between 0 and 10)

The file should contain a header and have the following format:

id	quality

1	1

# Acknowledgement

We thank P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis for providing this dataset.
