
## Adult Census Income

This dataset is provided for income prediction for individuals, it originally included income for all the countries, but I had it only show the US income, for better predicting the relationships. Our goal is to find any kind of correlation between individual income and other contributing factors that have been stated in our data. In my analysis I have tried to compare most of the important contributing factors to individual's income. Here are the ones that have been brought into visualizations:

 -  The first factor, that we compare is 'age' to see if individual's age has any relationship with their income, bellow chart, shows that in general,
individual's income has direct relationship with their age, it shows that the average age of income earner over 50K is 44 and the average age of under 50K earner is 37, our conclusion is, individuals pay gets higher as they get older (probably due to experience). In this report color Blue shows income over 50K and color Orange shows income bellow 50K)

| Income | Age |
| --- | --- |
| Over 50K | 44.3 |
| Under 50K | 37.8 |

![age1](https://user-images.githubusercontent.com/69549323/105791460-ffd7b280-5f3a-11eb-9a64-7e6fafc97fcc.png)



-  The next factor, that we want to measure is the gender, from our survey, it shows that 66%(2/3) of the participants were male and 33% were female(1/3), our plot shows that in income level under 50K, the distribution is normal for male and female but for income over 50K, it can be seens, that female percentages compare to male is about 20% (instead of being 33%), so we can conclude that the gender is another factor that effects individual's income. 

| Gender | Percentage |
| --- | --- |
| Male | 0.66 |
| Female | 0.33 |
 
![gender1](https://user-images.githubusercontent.com/69549323/105798893-0b7da600-5f48-11eb-8444-962376c2d19e.png)
 
 
-  The next factor that we take into consideration is 'hours_per_week', our chart shows that people who make over 50K on average work more than 40 hours compare to  the ones that are in under 50K category, so we conclude that hours_per_week is related to individual's income level.

![hours](https://user-images.githubusercontent.com/69549323/105799200-ca39c600-5f48-11eb-9323-22a6b29bc566.png)


-  The next factor is education level, our plot, shows that for education level Bachelor and higher on average, the number of individuals with income more than 50K are higher than the ones who make less, so we conclude, having education level bachelor or higher, is one of the important factors in making more money. Another noticeable factor that can be seen in the same chart, is, this works mostly for male, as it appears, for females, getting bachelor's and masters did not help females as much as it helped males with getting into 50K+ pay range.  

![education](https://user-images.githubusercontent.com/69549323/105799410-4fbd7600-5f49-11eb-8b38-21d349ac0907.png)


-  The next factor is race, our chart shows that the gap between number of white and black people making over 50K is much more than the gap between the white and black people making less than 50K, so being white might be another factor that contribute to higher than 50K income, in the next chart, it compares the race with the level of education and income, which confirms our last finding which shows that number of white people with bachelors making over 50K are much higher than the black ones, in comparison with the percentage among all the income levels.

![race1](https://user-images.githubusercontent.com/69549323/105800208-10902480-5f4b-11eb-867e-df50963245e1.png)

![race](https://user-images.githubusercontent.com/69549323/105799964-952e7300-5f4a-11eb-93f2-d9996d99b191.png)

# Conclusion: 
From our data we can conclude that the features that have direct correlation with income levels are:
-  Age: as people get older their pay range increases, that is probably due to experience/promotion ...
-  Gender: In general males are getting paid more than their female counterparts
-  Hours Per Week : people who work more than 40 hours a week appear to have higher pay than the ones who work less than 40 hours, this can be due to people having more than one job or the ones with higher pays are expected to work more by their manger/company
-  Race: our data shows that the race is a contributing factor in higher income, as it appears white people getting paid more than their non_white counterparts 
-  Education Level : In general people who hold Bachelor degree or higher are expected to get paid more than 50K, however, this trend can be challenged for females and other races, our  findings shows that this trend works for white males only.

