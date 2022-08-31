# A/A/B_test_result_analysis

<b>Investigate the user behavior for a company's app that sells food products.
The designers would like to change the fonts for the entire app, for which they decide to make a decision based on the results of an A/A/B test.   

![A/A/B test result analysis.](images/food_company_aab.jpg 'A/A/B test result analysis.')   

<b>The users are split into three groups: two control groups get the old fonts and one test group gets the new ones. Find out which set of fonts produces better results.
<b>Creating two A groups has certain advantages. We can make it a principle that we will only be confident in the accuracy of our testing when the two control groups are similar. If there are significant differences between the A groups, this can help us uncover factors that may be distorting the results. Comparing control groups also tells us how much time and data we'll need when running further tests.   

# Data Exploration.   

#### Event Dates
![Event dates.](images/aab_event_dates.png 'Event dates.')  
<b>We see effective use of the app only by 31st of July 2019 ...We literally don't see any values prior to it from   
the dates 25-30 of July 2019.  

#### Frequency of different events  
![Event frequency.](images/aab_event_frequency.png 'Event frequency.')   
<b> From the above graph , we see that more visitors are there for MainSreen which also includes some repeated users

#### Unique Users
![Unique users.](images/aab_unique_user.png 'Unique users.')   
<b>The above graph has a trend similar to the one we saw early..MainScreen being the most performed action  
followed by Offers ,then cart and finally payment . Since Tutorials is way few in numbers , we will analyse the other 4 actions.  

#### Percent of eventss occuring atleast once.  
![Event percent.](images/aab_action_percent.png 'Event percent.')   
<b> Since 'Tutorial ' is the least preferred action ,it has highest percent of single tiime as it has no repeated users.  
Main page has more visitors which shows with slightly reduced bar compared to other events.   

#### Event funnel.  
![Event funnel.](images/event_funnel.png 'Event funnel.')   
#### Conclusion:  
Around 56%of users move from Main screen to Offers page. From there ,around 42% moves ahead to Cart page.  
And finally around 25% from the cart page ends up paying for the transaction .  
Overall only 6% of users in MainScreen completes the sequence by payment .   
We see that more users are stuck at Cart page and don't turn up to Payment ..Though not as small as Cart page ,  
Offers page also shows lesser turn out of around 42%.  

#### Users visiting main screen
![Main screen.](images/users_main.png 'Main screen.')  

#### Users visiting offer screen
![Offer screen.](images/users_offer.png 'Offers screen.')  

#### Users visiting cart screen
![Cart screen.](images/users_cart.png 'Cart screen.')  

#### Users visiting payment screen
![Payment screen.](images/aab_users_payment.png 'Payment screen.')   
#### We don't see much difference in the groups based on the events.

# Final Conclusion.   
Based on the given data we see that  
1.Only 6% of the users viewing the Mainscreen finishes the sequence by doing payment.  
2.'Tutorial' is the least performed action .So we continued analysis with the rest 4 events.  
3.The number of user getting to next stage of the sequence gets reduced gradually from Main page  
but gets down to 25% when going to payment page.   
4.Comparing eah group , we see that all 3 shows similar trend in tems of different events .  
Since we have just a week data ,it's better to wait for few more days before concluding if the   
change of fonts impacts the performance of the app.





