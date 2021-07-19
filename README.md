# Global_Suicides_Number_Prediction

This project is the analysis of the Global Suicides Rates to understand the reasons that contribute to the increases number of suicides. This project uses the data from WHO taken since 1987. This data is extracted from https://www.kaggle.com/rushirdx/suicide-rates-from-1986-to-2016.

This analysis will give us the chance to understand factors affecting suicide rates and make a plan to take an action to remedy those factors. The aim is to get facts based plan of action for tackling increasing suicide rates.

We will explore effect of various factors including Age Groups, GDP and Sex.

1. General trend of population since 1987.

![Unknown-27](https://user-images.githubusercontent.com/31748299/126115561-59f0ce62-22ab-40b2-8a73-088ab2bdbe78.png)

2. General trend of GDP per Capita since 1987.

![Unknown-28](https://user-images.githubusercontent.com/31748299/126115752-b3719c70-230d-4a32-96d9-1c635ef3337e.png)

3. Effect of GDP per Capita on Number of Suicides

![Unknown-25](https://user-images.githubusercontent.com/31748299/126115871-b69cdd8d-ba8d-44ca-955f-81d125276cca.png)

4. Effect of Sex on Number of Suicides

![Unknown-20](https://user-images.githubusercontent.com/31748299/126115974-20cb787f-a9f0-4319-b3ee-3e8a8f988bba.png)

![Unknown-17](https://user-images.githubusercontent.com/31748299/126116082-6628fe24-1d2e-4d6c-8323-1f5b64cbe35b.png)

5. Effect of Age Group on Number of Suicides

![Unknown-23](https://user-images.githubusercontent.com/31748299/126116301-18829ae7-d946-46c6-b614-65b7ab00731d.png)

![Unknown-21](https://user-images.githubusercontent.com/31748299/126116490-17dbef40-2ae2-4af3-800d-c900684b82aa.png)

6. Correlation Heatmap

![Unknown-24](https://user-images.githubusercontent.com/31748299/126116603-7a1ea61f-5d1c-4563-813d-0cc2bc9dec38.png)

After getting a basic idea of what data we are dealing with, we created the dataset for input to machine learning models.
We tried multiple models to check which model gives the best result.

After trying many models, we got that Random Forest Regression Model gives the best results with the accuracy of almost 72%.

Feature Importance:

![Unknown-29](https://user-images.githubusercontent.com/31748299/126116921-94f29179-5c71-4141-aed5-9d42e602563b.png)


Conclusion:
1. If we look at the number of suicides/100k population, surprisingly most suicides are for age group 75+. Older people tend to be ignored in the society and feel lonely. 

Sol: To give extra attention to older people and make them feel part of the community.


2. Historically, there is a lot of pressure on males in the society to be a successful bread winner and be mentally strong. I think this takes a toll. We should focus on the mental health of males. 

Sol: Give attention to the Men's mental health.


3. Not at all surprisingly, GDP_per_capita plays a big role in the number of suicides. Higher GDP_per_capita indicates better quality of life and opportunities.

Sol: Focus on developing country's financial condition and business as well as investment development of the country.
