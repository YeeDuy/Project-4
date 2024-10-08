# Introduction
With this project we wanted to create an algorithm to predict the outcome of healthy patients (as opposed to patients with heart disease) based on certain factors such as high cholesterol or smoking habits. To do this an algorithm was made to help predict the possibility of heart disease based on potential telling factors, and the BRFSS had readily available data for us to use and test for this exact purpose. While the original dataset is on Kaggle that was already clean, we had decided to clean this dataset ourselves in order to create a better fit.

# Link to Presentation
https://docs.google.com/presentation/d/1OXDKEVJd5geLujpc856oedN7ZHAz6vrUeVhBLGG76Yk/edit?usp=sharing

### Column Classification: 
* For anyone wishing to know the columns in detail, we referred to what the author mentioned in the datacard and got this (do check the original out in case you're unsure about any):
  *  HighBP : Indicates if the person has been told by a health professional that they have High Blood Pressure.
  *  HighChol : Indicates if the person has been told by a health professional that they have High Blood Cholesterol.
  *  CholCheck : Cholesterol Check, if the person has their cholesterol levels checked within the last 5 years.
  *  BMI : Body Mass Index, calculated by dividing the persons weight (in kilogram) by the square of their height (in meters).
  *  Smoker : Indicates if the person has smoked at least 100 cigarettes.
  *  Stroke : Indicates if the person has a history of stroke.
  *  Diabetes : Indicates if the person has a history of diabetes, or currently in pre-diabetes, or suffers from either type of diabetes.
  *  PhysActivity : Indicates if the person has some form of physical activity in their day-to-day routine.
  *  Fruits : Indicates if the person consumes 1 or more fruit(s) daily.
  *  Veggies : Indicates if the person consumes 1 or more vegetable(s) daily.
  *  HvyAlcoholConsump : Indicates if the person has more than 14 drinks per week.
  *  AnyHealthcare : Indicates if the person has any form of health insurance.
  *  NoDocbcCost : Indicates if the person wanted to visit a doctor within the past 1 year but couldn’t, due to cost.
  *  GenHlth : Indicates the persons response to how well is their general health, ranging from 1 (excellent) to 5 (poor).
  *  Menthlth : Indicates the number of days, within the past 30 days that the person had bad mental health.
  *  PhysHlth : Indicates the number of days, within the past 30 days that the person had bad physical health.
  *  DiffWalk : Indicates if the person has difficulty while walking or climbing stairs.
  *  Sex : Indicates the gender of the person, where 0 is female and 1 is male.
  *  Age : Indicates the age class of the person, where 1 is 18 years to 24 years up till 13 which is 80 years or older, each interval between has a 5-year increment.
  *  Education : Indicates the highest year of school completed, with 0 being never attended or kindergarten only and 6 being, having attended 4 years of college or more.
  *  Income : Indicates the total household income, ranging from 1 (at least $10,000) to 6 ($75,000+)
