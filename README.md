# Project 2: World Peace Through Foreign Aid

Collaborators: Rosalyn Brown, Dean Kim, Thomas Scott & Samuel Simmons

[Presentation Link](https://github.com/ThomasJScott3/Project-2/blob/main/World%20Peace%20Through%20Foreign%20Aid.pdf)

Goal: The goal of this project was to target which countries in South America should be receiving foregin aid based on their economic performance and which should not. We used a machine learning strategy called linear regression to evaluate various economic trends in those countries. If the trends were positive, they should not receive foreign aid. If the opposite was true, then the countries should receive foreign aid. In addition, we created wordclouds to qaulify and clarify our findings.

Libararies Used: Pandas, Matplotlib, Sklearn, Newsapi & Nltk
## Analysis:

In this section, we will evaluate which nations should or should not receive foreign aid.

### Bolivia
Should receive aid: No

Charts:

<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Charts/Bolivia/Bolivia%20Balance%20of%20Payments%20Projection.png"></img></p>

<br>

<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Charts/Bolivia/Bolivia%20GDP%20Pct%20Change%20Projection.png"></img></p>

<br>

Wordcloud:

<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Word%20Clouds/Bolivia.png"></img></p>

<br>

Explanation:

<br>
As you can clearly see from the visuals, the balance of payments for Bolivia has been increasing. Although the scatter plot is somewhat cyclical, the trend line shown by the linear regression shows an upward trend toward net positive balance of payments for the country. This indicates a healthy trend. Moreover, the GDP change is trending upward. As such, foreign aid should not be disbursed despite the wordcloud showing that COVID is a concern in international news media about the country. 

<br>

### Argentina
Should receive aid: No

Charts:

<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Charts/Argentina/Argentina%20CPI%20Projection.png"></img></p>

<br>

<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Charts/Argentina/Argentina%20GDP%20Projection.png"></img></p>

<br>

<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Charts/Argentina/Argentina%20USD%20Exchange%20Rate%20Projection.png"></img></p>

<br>

Wordcloud:
<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Word%20Clouds/Argentina.png"></img></p>

<br>

Explanation:
<br>
This one is a bit more tricky. Although the trend for CPI shows a clear inflationary trend, this is counterveiled by flat GDP growth. Although this might otherwise indicate that foreign aid would be appropriate, we instead recommend [dollarization](https://www.cbaeconomia.com/dollarization.pdf), which would allign the value of the Argentine Peso with that of the dollar. Given the rising exhcange rate between the two currencies as shown in the third visual, this step would likely be much more appropriate than simply sending funds directly to a [profligate government in Buenos Ares](https://en.wikipedia.org/wiki/Argentine_debt_restructuring). In addition, the presence of more data points in the third linear regression back up the validity of these findings.
<br>
### Colombia

Should receive aid: Yes

Charts:

<p align="center"><img src="https://github.com/ThomasJScott3/Project-2/blob/main/Images/Charts/Colombia/Colombia%20Exchange%20Rate.png"></img></p>
  
<br>

<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Charts/Colombia/Colombia%20GDP%20Percent%20Change.png"></img></p>

Wordcloud:

<br>

<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Word%20Clouds/Colombia.png"></img></p>

<br>

Explanation:
<br>
The trend in CPI and GDP growth both illustrate the need for urgent assistance here. First, there is clearly an inflationary issue that is relatively recent compare to Argentina. In addition, the GDP trend shows a negative trend in economic growth. This shows the strength of linear regression. Scatter plots make data points look disorganized, but a regression line can help show clear trends in the data. In addition, there was a great deal more data for CPI, making for a solid regression model. Finally, a phrase that sticks out in the word cloud is "social unrest" insinuating that this country is a prime target for aid.
<br>
### Chile
Should receive aid: Yes

Charts:

<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Charts/Chile/Chile%20CPI.png"></img></p>

<br>

<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Charts/Chile/Chile%20Exchange%20Rate.png"></img></p>

<br>

<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Charts/Chile/Chile%20GDP%20Pct%20Change.png"></img></p>

<br>

Wordcloud:

<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Word%20Clouds/Chile.png"></img></p>
  
<br>
  
Explanation:

<br>
This set of visuals show an inflationary trend that has only gotten <a href="https://www.bloomberg.com/news/articles/2021-08-06/chile-inflation-surges-past-target-range-ceiling-to-5-year-high">worse during the coronavirus crisis</a>. In addition, the GDP growth trend has slowed in recent year and the regression shows a negative trend. Both the exchange rate and the CPI show a clear slide of the Chilean Peso against the dollar. Just like previous examples, there are a lot more CPI data points to back up this point. Finally, the word cloud shows possible <a href="https://www.reuters.com/article/us-metals-copper-ahome-idUSKBN2FH1LZ">disruption in commodities exports</a>.
<br>

### Brazil
Should receive aid: Yes

Charts:

<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Charts/Brazil/Brazil%20CPI%20Projection.png"></img></p>
  
<br>

<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Charts/Brazil/Brazil%20Exchange%20Rate%20Projection.png"></img></p>
  
<br>

<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Charts/Brazil/Brazil%20GDP%20Change%20Projection.png"></img></p>

Wordcloud:

<p align="center"><img src="https://raw.githubusercontent.com/ThomasJScott3/Project-2/main/Images/Word%20Clouds/Brazil.png"></img></p>
  
<br>

Explanation:

The data points here show clear inflationary trend. Like prior CPI plots, there are a large quantity of data points to back this up. The exchange rate also shows an slide, albeit a cyclical one, against the dollar. Finally, there is a discernable downward trend in GDP growth that is of concern. Finally, the word cloud did not produce results that are of relevance here. In the future, a more refined algorithm specifically for Brazil might be warrented.  

### Conclusion

In conclusion, there are limits to what can be concluded by our findings. Changes in exchange rate and CPI are cumulative and can be unnoticable if paired with robust economic growth. Finally, the decline in GDP growth might not be as dire as the data shows at second glance. A mere decline in GDP growth _per se_ does not mean that a nation's economy has stopped growing, just that it is not growing as fast. This brings me to my final point, the data that we obtained from the IMF and World Bank is limited and should only be used in the context of an academic exercise. In this case, our fictitious congressional hearing was just that. 
