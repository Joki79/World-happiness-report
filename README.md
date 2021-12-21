# World-happiness-report
This project is focusing on cleaning, visualizing and analyzing data


In this project I have analyzed the data on happiness index. In the part 1 I have cleaned my data and kept only countries that had data for entire period 2015-2019.
In the part 2 I focused on visualizing data and the data distribution. I have used geoplots, histograms, Q-Q plots for testing data normality and box and whisker plots to get the better insight into data. 
The part 3 was focused on data analysis and the development of the potential model. There were couple of limitations. The data collected was over 4 years and it is hard to talk off a trend. However I analyzed the existing data and the features over those 4 years in order to determine which feature was affecting the happiness index the most and which feature was becoming more important. 
Another limitation waas the fact that the happiness index is actually the sum of all  feature values. Therefore the linear regression with all featutres was not an appropriate choice of model. Instead I have used only the most importan features for my model and achieved the r^2 score of 64%.
