Layoff Prediction Using Financial Sentiment Analysis

Briefly describe the purpose/result(s) of your project, the skills you applied, and the AI4ALL Ignite program.
*Uncovered and meticulously analyzed three distinct biases present in ChatGPT, employing advanced Python techniques and data analysis methodologies, all within AI4ALL's cutting-edge AI4ALL Ignite accelerator.*


## Problem Statement <!--- do not change this line -->

(UPDATE IN README.md)
Describe the motivation for this project, why it is relevant, and what its impacts are.

*EXAMPLE:*
*Given the substantial daily output of responses, the identification and mitigation of ChatGPT's biases become critical, safeguarding both the multitude of users and the far-reaching consequences they may influence.*

## Key Results <!--- do not change this line -->

Recorded over 1,000 data points and anlayzed the results
Identified two biases in data from layoffs.fyi
Selection Bias
Platform/Source Bias


## Methodologies <!--- do not change this line -->

GenAI Adoption Flag (Binary): Indicates if GenAI was adopted by the quarter
Layoff History: 4-quarter rolling sum of layoffs (temporal context)
Employee Sentiment: Polarity score (-1 to 1) from TextBlob analysis of reviews
Neutral (0) for pre-adoption quarters or missing reviews
Quarter Cyclical Encoding:
quarter_sin/quarter_cos for seasonal trends


## Data Sources <!--- do not change this line -->

Kaggle Dataset: Link to Kaggle Dataset

Layoffs Dataset: Link to Layoffs Dataset

## Technologies Used <!--- do not change this line -->

(UPDATE IN README.md)
List the technologies, libraries, and frameworks used in your project.

*EXAMPLE:*
- *Python*
- *pandas*
- *TensorFlow*


## Authors <!--- do not change this line -->

*This project was completed in collaboration with:*
- *Rohit Chivukla (abhi.chivukula@gmail.com)*
- *Emma Hsieh (eh5775@princeton.edu)*

