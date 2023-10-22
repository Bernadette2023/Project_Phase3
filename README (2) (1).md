# PREDICTION OF INFLUENCE IN VACCINATION RATES
![Title](https://github.com/Bernadette2023/Project_Phase3/blob/main/Untitled%20Folder/h1n1-vaccine.jpg?raw=true)

# Business understanding and problem overview
The goal of this project is to predict the likelihood of individuals receiving the H1N1 seasonal flu vaccine. Understanding how various factors, including demographics, health behaviors, and opinions, relate to vaccination patterns can provide valuable guidance for future public health efforts.

# Data understanding
This project aims to predict seasonal flu vaccine uptake based on a survey conducted by the National 2009 H1N1 Flu Survey. The dataset contains 38 columns, including:

 - Demographic and socioeconomic factors
 - Health-related behaviors
 - Opinions on vaccines
 - Geographic and household information
 - Employment details

# Target Variable
seasonal_vaccine: Whether the respondent received the seasonal flu vaccine (our primary target).






# Exploratory Data Analysis
Here are a few of the analyses between the target variables and the other variables.

Here is a comparison between those who got the vaccine and those who didn't.
![Graph](https://github.com/Bernadette2023/Project_Phase3/blob/main/Untitled%20Folder/Capture.PNG)


Here is a relationship between the target variable and Age.

![Graph](https://github.com/Bernadette2023/Project_Phase3/blob/main/Untitled%20Folder/AGE.PNG)



# Modelling the data
# Model 1
The data is ready for modeling and here I am using Logistic regression to create a baseline model.

The data gave an accuracy of 0.710

![Model 1 results](https://github.com/Bernadette2023/Project_Phase3/blob/main/Untitled%20Folder/Capture%201.PNG)



# Model 2
Here, a more complex model - a Random Forest Classifier to achieve the performance.

The data gave an accuracy of 0.787

![Model 2 results](https://github.com/Bernadette2023/Project_Phase3/blob/main/Untitled%20Folder/Capture%203.PNG)



# Model 3
The data was used to fine-tune by adding hyper-parameters to give a better performance.

The data gave an accuracy of 0.795

![Model 2 results](https://github.com/Bernadette2023/Project_Phase3/blob/main/Untitled%20Folder/Capture3.PNG)
# Summary
The final model I chose is Model 3. This is the reason:
- Baseline Model Accuracy: 0.710
- After Hyperparameters Accuracy: 0.795

Model 3 outperformed the other models in terms of accuracy. The increase in accuracy from the baseline model (Model 1) to the final model (Model 3) demonstrates the value of hyperparameter tuning in improving model performance.

# Recommendations
Public Awareness Campaigns:
Launch comprehensive public awareness campaigns to educate the public about the importance of the H1N1 vaccine. Highlight its effectiveness in preventing the spread of the virus and the potential severity of H1N1 influenza.

Healthcare Provider Involvement:
Encourage healthcare providers to actively recommend the H1N1 vaccine to their patients. The recommendation of a trusted healthcare professional can significantly influence individual vaccination decisions.

Transparency and Communication:
Maintain transparent and open communication with the public regarding the development, testing, and safety of the H1N1 vaccine. Address concerns and misconceptions promptly to build trust.





































