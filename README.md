# aab_test_result_analysis

Investigate the user behavior for a company's app that sells food products.
The designers would like to change the fonts for the entire app, for which they decide to make a decision based on the results of an A/A/B test.   

![A/A/B test result analysis.](images/food_company_aab.jpg 'A/A/B test result analysis.')   

The users are split into three groups: two control groups get the old fonts and one test group gets the new ones. Find out which set of fonts produces better results.
Creating two A groups has certain advantages. We can make it a principle that we will only be confident in the accuracy of our testing when the two control groups are similar. If there are significant differences between the A groups, this can help us uncover factors that may be distorting the results. Comparing control groups also tells us how much time and data we'll need when running further tests.   

# Data Exploration.   

#### Event Dates
![Event dates.](images/aab_event_dates.png 'Event dates.')  

#### Frequency of diffderent events  
![Event frequency.](images/aab_event_frequency.png 'Event frequency.')   

#### Unique Users
![Unique users.](images/aab_unique_user.png 'Unique users.')   

#### Percent of eventss occuring atleast once.  
![Event percent.](images/aab_action_percent.png 'Event percent.')   

#### Event funnel.  
![Event funnel.](images/newplot (6).png 'Event funnel.')   


#### Users visiting main screen
![Main screen.](images/users_main.png 'Main screen.')  

#### Users visiting offer screen
![Offer screen.](images/users_offer.png 'Offers screen.')  

#### Users visiting cart screen
![Cart screen.](images/users_cart.png 'Cart screen.')  

#### Users visiting payment screen
![Payment screen.](images/aab_users_payment.png 'Payment screen.')   

# Final Conclusion.   
Based oon the given data we see that  
1.Only 6% of the users viewing the Mainscreen finishes the sequence by doing payment.  
2.'Tutorial' is the least performed action .So we continued analysis with the rest 4 events.  
3.The number of user getting to next stage of the sequence gets reduced gradually from Main page  
but gets down to 25% when going to payment page.
4.Comparing eah group , we see that all 3 shows similar trend in tems of different events .  
Since we have just a week data ,it's better to wait for few more days before concluding if the   
change of fonts impacts the performance of the app.





