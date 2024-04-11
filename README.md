
# FAKE NEWS DETECTION - A Machine Learning Project 

![image](https://github.com/melisatahiraj/Project_4/assets/147290574/1253e92e-a831-4365-bff9-37d296461fcd)

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

## DATA OUTPUTS 

### Feature Selection

  ![image_480_480](https://github.com/melisatahiraj/Project_4/assets/147290574/495e006a-c7aa-4d03-a801-2c45a7c712d1)

  ![image_720](https://github.com/melisatahiraj/Project_4/assets/147290574/b16618a5-9df1-406a-ac43-e978f6cf255c)

  ![image_480_480](https://github.com/melisatahiraj/Project_4/assets/147290574/0ae2c4dd-9fd3-4fdd-9941-f442f67ebd2e)

  ![download_480](https://github.com/melisatahiraj/Project_4/assets/147290574/b6507a2c-e0e0-4715-811a-90e13f701786)

  ![image](https://github.com/melisatahiraj/Project_4/assets/147290574/dff9d9fb-35d3-4a71-afa5-fb0b283cae9c)
  
  
### Random Forest Model 

  ![image](https://github.com/melisatahiraj/Project_4/assets/147290574/b4dd65ed-1350-47ee-b50e-443886773a07)

  ![image_360](https://github.com/melisatahiraj/Project_4/assets/147290574/7e952aea-6ee0-48a2-8786-f1883fb2837a)

  ![download_480](https://github.com/melisatahiraj/Project_4/assets/147290574/6dff682f-caef-42b4-8945-d7ffce7307b1)

### Logistic Regression 

  ![screenshot_2024-04-09_at_11 40 42___pm_480_360](https://github.com/melisatahiraj/Project_4/assets/147290574/1d78e618-ba5d-4d63-8547-bb3cfacbaf4e)

  ![download_360](https://github.com/melisatahiraj/Project_4/assets/147290574/4fc5e0ee-5064-47b0-92d8-284119fdd991)

  ![download_480](https://github.com/melisatahiraj/Project_4/assets/147290574/2328e94f-929b-4be3-9b2d-30153ccaeed5)

### Recurrent Neural Network 

  ![screenshot_2024-04-09_at_11 41 24___pm_480_480](https://github.com/melisatahiraj/Project_4/assets/147290574/a19efe40-e90a-4dad-b4c9-7078f8c3f73a)

  ![screenshot_2024-04-09_at_11 44 33___pm_480_480](https://github.com/melisatahiraj/Project_4/assets/147290574/fb2eab66-9b1d-4d5d-a471-a89d6359bd53)

  ![download_480](https://github.com/melisatahiraj/Project_4/assets/147290574/a9954815-3be6-4684-a095-25c1c00b424f)

### Visualizaton 

  Word Cloud 

   ![screenshot_2024-04-09_at_2 17 58___pm_720](https://github.com/melisatahiraj/Project_4/assets/147290574/1ea59750-4463-453c-81af-1ffb8d6ebccb)   
   
   ![screenshot_2024-04-09_at_2 18 07___pm_720](https://github.com/melisatahiraj/Project_4/assets/147290574/a7ec02fc-5a4d-44e3-adf0-731d3332f00f)

  Pairplot 

   ![download_720](https://github.com/melisatahiraj/Project_4/assets/147290574/83176bcd-4ac9-4934-bb0d-fe0894175b98)

# Contributions: 

  ![image_720](https://github.com/melisatahiraj/Project_4/assets/147290574/4a32c42e-261a-481a-bb63-259d50a707ee)

# References: 

  Kaggle - https://www.kaggle.com/datasets/arashnic/fake-claim-dataset

  Michigan University Library - https://guides.lib.umich.edu/c.php?g=283063&p=4471741

  

   

  

  
  

  

  

  


  

  

  

  

  




