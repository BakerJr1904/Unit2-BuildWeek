# Unit2-Sprint4-BuildWeek
### I went above and beyond with this Build Week
We had one weekend to finish the assessment, and learn Plotly/Dash and create a Plotly/Dash app. I was actually the only person that went above and beyond creating 3 Plotly/Dash apps. Two people did web-apps, and the rest of the class didn't turn that part in. My Plotly/Dash apps are hosted on Heroku.<br/>
This first one was just practice which consisted of a scatter plot and a map. After that I did an animation scatter plot, just because I thought it would show my skills and motivation. I was running out of time but, I saw a sunburst plot that I just had to do. All of which are fully interactive Plotly/Dash apps.<br/>
[My Practice Plotly/Dash App](https://data-science2021.herokuapp.com/)<br/>
[My Animated Plotly/Dash App](https://data-science2021-2.herokuapp.com/)<br/>
[My SunBurst Plotly/Dash App](https://data-science2021-3.herokuapp.com/)
### The Assignment 
(This notebook was made and can run in Google Colab, modifications may be needed to run elsewhere.)<br/>
Take the Kaggle Life Expectancy CSV file, and wrangle the data. This consisted of cleaning the data and Feature Engineering and Encoding the data. Then we needed to split and scale the data, but we only want to scale (X), we don’t want to scale what we are trying to predict (y). I used StandardScaler(). My target was Life Expectancy. I used Matplotlib to plot the value counts of (y). the data was split into a training set, a validation set and a testing set. The Baseline accuracy was then predicted.  A Random Forest pipeline was used with OrdinalEncoder(), SimpleImputer(), and RandomForestRegressor(). The Training Accuracy and Validation Accuracy were then returned. The Gini Coefficient or Gini Index was used to measure feature importance. Higher the value of an index, more dispersed is the data. Alternatively, the Gini coefficient can be looked like half of the relative mean absolute difference. Gini index is the most commonly used measure of inequality. HIV/Aids had the greatest importance by a huge amount, but if you take that feature out another feature would take its place as the greatest importance by a huge amount. This has to do with the data...The data had many things that can cause death<br/>



<br/>
