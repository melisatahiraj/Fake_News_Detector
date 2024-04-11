
# FAKE NEWS DETECTION - A Machine Learning Project 

## Project Team 

| NAME              | SLACK HANDLER  |         GitHub Repo              |
| -------------     | -------------  |--------------------------        |
| Dianna Stafford   | @DeStafford    | https://github.com/DeStafford    |
| Marlene D Holman  | @MdataHolman   | https://github.com/MdataHolman   |
| Melisa Tahiraj    | @melisatahiraj | https://github.com/melisatahiraj |
| Melissa Acevedo   | @mzacevedo     | https://github.com/mzacevedo     |

## Presentation Link here: [FAKE NEWS DETECTION - A Machine Learning Project](https://prezi.com/view/ONA9JoBIeEWizRopv8uQ/) 

## Project Overview 

### 1. Introduction:

The widespread use of social media platforms has transformed the way information is disseminated and consumed, but it has also given rise to the proliferation of false information and fake news. Traditional methods of manual supervision are unable to cope with the sheer volume and speed of content on these platforms. To address this challenge, this project proposes the development of advanced deep learning models to automatically detect false short-text claims on social media

### 2. Objectives:

* To develop a machine learning model capable of automatically detecting false information and fake news within short-text posts on social media.

* To create a dataset comprising a diverse range of false and true short-text claims from various social media platforms for training and evaluation purposes.

* To identify key features and factors influencing the classification of social media posts as fake or real.

* To design and implement a scalable and efficient system for real-time monitoring and flagging of false information on social media platforms.

* To evaluate the performance of the model through rigorous testing and comparison with existing methods, demonstrating their effectiveness in mitigating the spread of misinformation.

### 3. Methodology:

  **Loading the data** - from Kaggle

  **Exploratory Data Analysis** - Describing the data, column datatypes, nulls, size, etc.

  **Data Cleaning** - Removing punctuations, dropped columns, data manipulations, removing nulls and getting the Outliers. 

  **Data Visualization** - Creating histograms, heatmaps, boxplots, pairplot, and bar graphs. 

  **Label Encoding** - Convert Categorical variables to numerical. 

  **Train & Test Split** - Split test and train data as 20% and 80% respectively. 

  **Feature Importance** - Anova and Random Forest Classifier & selected Top 6 features. 

  **Data Modeling** - Trained the Random Forest Classifier & Logistic Regression. 

  **SMOTE** - Handling of Overfitting

  **Data Evaluation** - F1 Score, R2 Squared, RMSE, MSE, Accuracy, and Confusion Matric. 

  ![Work_Flow_Chart](https://github.com/melisatahiraj/Project_4/assets/147290574/cb0734e3-e2ca-44d7-9b68-4ed0b40b6d94)


### 4. Expected Outcomes:

  * Development of state-of-the-art deep learning models capable of accurately detecting false short-text claims on social media platforms.

  * Creation of a benchmark dataset for evaluating false claim detection algorithms in the context of social media.

  * Insights into the effectiveness and limitations of different deep learning architectures for this task.

  * Demonstration of the potential for automated detection systems to assist in combating the spread of misinformation online.


### 5. Impact and Significance:

  * The project aims to contribute to the ongoing efforts to combat the spread of false information and fake news on social media platforms.

  * Automated detection systems developed through this project could assist social media platforms, fact-checking organizations, and users in identifying and flagging misleading content.

  * Ultimately, the project seeks to foster a healthier online information ecosystem by empowering users with tools to discern credible information from false claims.

### 6. Conclusion:

>> Here's what we concluded:

1. On Important Features >  By looking at which words and contexts matter most, our model runs on a consistent feature to find our accurate performance scores. We got a better idea of what makes fake news different from real news. This could help us make better detection models in the future.

2. On Model Performance >>. The best model was the recurring neural network, Tensor Flow, which accurately predicts fake news. 

3. On Challenges >> We encountered several issues like having too few examples from our dataset as well at the beginning we had an imbalance of data which we resolved successfully in one or two ways by using the most fitting Machine Learning model. 


**What's Next?**

We could do: 

1. **Improving Models**: We can make our models even better by tweaking them or trying new techniques.

2. **Getting Better Data**: Adding more types of news articles and other info could make our models work in more situations.

3. **Making It Work Everywhere**: Checking our models if they worked well with new data and looking at ways to handle lots of news articles and changes in the news world.

4. **Putting It into Action**: Figuring out how to use our models on websites and social media could help stop fake news from spreading fast.

>> In the end, our project moves us forward in the fight against fake news. By using machine learning, it is our hope we're getting better at spotting fake stories and making our online world more trustworthy.
