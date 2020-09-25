# Survey on Education Loan in the U.S.

[rmd file](https://github.com/QMSS-G5063-2020/Zijin_Zhou/blob/master/hw01/hw01.Rmd)

[html](https://github.com/QMSS-G5063-2020/Zijin_Zhou/blob/master/hw01/hw01.html)

[html.nb](https://github.com/QMSS-G5063-2020/Zijin_Zhou/blob/master/hw01/hw01.nb.html)

Here is a clean version of my work(without codes):
## 1.Debt over time
### Debt and debt ratio over time
![Chart 1](https://github.com/QMSS-G5063-2020/Zijin_Zhou/blob/master/hw01/charts/chart1.png)

In chart1, the line chart shows the trend of average debt/asset ratio from 1989 to 2016 and the bar chart shows the trend of average debt from 1989 to 2016.   
Although the average amount of debt fluctuated, it did not make a great increase over the years. However, the debt-to-asset ratio increased in a great scale over time and even got over 1 after 2010.    
The combination of line and bar chart can show the amount of debt and the trend of ratio over year at the same time therefore this chart is proper for the research.

### The proportion of Student loan
![Chart 2](https://github.com/QMSS-G5063-2020/Zijin_Zhou/blob/master/hw01/charts/chart2.png)

Chart2 shows the proportion of the average of different loans every survey year.    
Comparing with other type of loans, student loan only takes a small proportion in debt (the largest is about 3% in 2016), but it got more important from 1989 to 2016. Mortage loan and installment loan are the top 2 loan among all the loans. Mortage loan takes more than a half proportion of the debt in most of the survey years.

### Student Loan over time
![Chart 3](https://github.com/QMSS-G5063-2020/Zijin_Zhou/blob/master/hw01/charts/chart3.png)

In chart3, the line chart shows the trend of average student_loan/debt ratio from 1989 to 2016 and the bar chart shows the trend of average student loan from 1989 to 2016.    
The proportion of the Student Loan in the line graph is calculated by EDN_INST/DEBT. Noted that there are many respondents without any debt, so these respondents are removed from this analysis. The proportions of student loan in this line graph are larger than the proportions in stacked 100% bar chart above because of the different calculation methods. The proportion and the average amount of student loan have been increasing over time.     
Regardlessness of the different nunmber in chart2 and chart3, the evidence shows that student loan does become more important over years.

The combination of line and bar chart can show the amount of student loan and the trend of ratio over year at the same time; however, it cannot indicates the other kinds of loans and there proportion in the debt. Chart2 can give the reader a direct feeling of the proportion of each loan and the change of student loan over years. Therefore, I recommand chart2 to show the growing importance of student loan over time.

## 2.Tell me who you are
### Get married and kids, get stable and broke.

This topic is a discussion of the relationship between student loan and the number of kids in different the marital status in 2016. I use two kinds of visualization in this discussion. The first, chart4, is a bubble chart with fit line by the method of loess. The second, chart5, is a dodged bar chart with the fit line.

**chart4: bubble and fit line**

![Chart 4](https://github.com/QMSS-G5063-2020/Zijin_Zhou/blob/master/hw01/charts/chart4.png)

The fit line and the location of the bubble in chart4 show the relationship between the number of kids and the student loan. The color shows the different marital status and the size of the bubble shows the number of respondents in each category which indicates the bias of this analysis.   
The stability here does not mean that marriage helps in saving money to make a more stable life. In fact, get married makes a stable and high expense for educational loans no matter how many children the household has. The average education loan in the married respondent is 8378.24 dollars, which is about 2000 dollars higher than the others. Also, we can tell from the lower standard deviation that the higher stability of expenses on educational loans that married people have.     
As for the people who are neither married or living with a partner, the average educational loan expenses can hit the top at almost 12000 dollars if they have 3 children; however, it goes down on a large scale when the number of children is over 3.       
Additionally, no matter married or not, people without kids usually pay fewer education loans as it shows in the graph.     
Noted that the result has a bias because the number of observations is relatively limited the more children the households have. 

**chart5: bar chart and fit line**   

![Chart 5](https://github.com/QMSS-G5063-2020/Zijin_Zhou/blob/master/hw01/charts/chart5.png)

We can draw the same conclusion as chart4 from chart5 except for the number of respondents in each category. Additionally, the bar chart in chart5 can tell the amount of average student loan more clearly.    

For getting more information, I think chart4 is better than chart5 in this topic. Chart4 not only displays the relationship between debt, kids and marriage, but shows the number of people in each category in the survey.

### Young, Smart but Poor

This topic discusses the relationship between age and student loan in different education background in 2016 with scatter and fit line (chart6).

![Chart 6](https://github.com/QMSS-G5063-2020/Zijin_Zhou/blob/master/hw01/charts/chart6.png)

Each point in the scatter plot shows the average student loan in an certain age and education background. The darker of the point's color, the higher education the respondent got. The fit line shows the relationship between age and student loan as a whole.   
The color in chart6 tells that people with high degree tend to have more student loan. For instance the average student loan of college degree people at age of 28 can be more than 55,000 dollars, while the one with other degrees are all less than 20,000 dollars.    
For all kind s of observations, the average student loan goes up with age before about 30, then it decrease as getting older. After about 70, the average amount of student loan get zero no matter the educational background.    

The scatter plot with color can give readers a clear information of the education background pattern and the fit line shows the relationship between age and student loan well. Therefore, Chart6 is suitable for this topic.

## 3.Wealth and Income Distribution

This section discusses the relationship between student loan and both networth and income in 2016 with two simple bar charts (chart7).

![Chart 7](https://github.com/QMSS-G5063-2020/Zijin_Zhou/blob/master/hw01/charts/chart7.png)

The bar chart on the left in chart7 shows that the average student loan increases then decreases as income going up. People in 40-60 percentile of income have the highest average student loan, 9266 dollars. This maybe because the higher-income class tends to spend more on education but they can pay more or pay off with there own income without the help of debt when the income gets even higher. Poor middle class:(    
However, the discussion on networth shows a totally different pattern. Less networth reveals more debt, especially first 20% (average student loan more than 17,000 dollars) as it displays on the right. People from 20% to 80% percentile have an average student loan between 4,000 and 6,000 dollars, while 80% to 100% have the average loan less than 2,000 dollars.

Two seperate bar charts can make reader understand the student loan in different networth and income and compare the patterns of them easily. Therefore, chart7 is recommend for discussing wealth and income distribution.

## 4.Going broke
### Bankruptcy and Student Loan

This part discusses the proportion of bankruptcy with and without student loans over time after 1998 because there is no bankruptcy reported in the original dataset before. 

![Chart 8](https://github.com/QMSS-G5063-2020/Zijin_Zhou/blob/master/hw01/charts/chart8.png)

The line graph shows how the proportion varies over time and the color indicates the difference of proportion in student loan status. The proportion of bankruptcy does not change in great scale from 1998 to 2016. The respondents with student loan do have a higher possibility (5.12%) of having bankruptcy compared with those who do not have a student loan (2.85%). 

Chart8 displays the difference in bankruptcy proportion with and without loan status by line chart. However, since there is no obvious trend over time, I suppose bar chart also matches this topic.


### food expense and go broke

Two kinds of charts are used in this discussion. Chart9 is a series of pie charts and chart10 is a stacked bar chart.

**pie chart**

![Chart 9](https://github.com/QMSS-G5063-2020/Zijin_Zhou/blob/master/hw01/charts/chart9.png)

Pie charts in chart9 show the proportion of different kinds of food expense in different broke status. No matter bankruptcy or foreclose, people without these problems spend more on food away from home.

**stacked bar chart**

![Chart 10](https://github.com/QMSS-G5063-2020/Zijin_Zhou/blob/master/hw01/charts/chart10.png)

The stacked bar chart indicates the amount of the expenses on food together with the proportion. For the bankruptcy, people with the problem spend less on delivery and away and also in total on average. As for people struggling with foreclose, though they have a higher proportion of home food expense, they still spend more than 2,000 dollars in total than those without foreclose issue. We can tell from chart10 that there is a non-thrifty behavior in foreclose.

Chart10 has a better performance than chart9 because it provides some extra information of the amount of the spending as well as the proportion. It can show the actual non-thrifty behavior of respondents compared with chart9. Therefore, I recommand use stacked bar chart here.

## interaction and data table

Please check the html file!
