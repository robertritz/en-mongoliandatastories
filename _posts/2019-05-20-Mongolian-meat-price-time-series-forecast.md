---
layout: post
title:  ### Mongolian Meat Price Time Series Forecast
date:   2019-05-20 00:00:00 +0800
image:  '/images/meat_prices/forecast.png'
tags:   [meat, prices, forecast]
featured: 
---

#### In the land of eternal blue skies and nearly 70 million animals, meat is getting expensive

Since September 2018 the average price per kilogram of mutton in Ulaanbaatar has increased by 35% (beef increased 26%). News outlets have been buzzing with talk of these price increases and even meat shortages. Headlines from many news outlets make it seem as if the sky is falling (see below for a particularly sensational headline from Ikon.mn). I hope to explain the market forces at play here and hopefully better understand why prices are at record highs.

![](/images/meat_prices/roller_coaster.png)

Time series of beef and mutton prices from 2011 to 2019.

#### How Meat Works in Mongolia

In Mongolia, meat prices are highly seasonal, with meat prices rising in the Spring and then falling in the Fall. The meat supply itself comes from nomadic herders who make up roughly 30% of the population. But these herders do not operate with anything resembling a western mode of production. Their behavior has more to do with herd health and preparations for the various challenges of each season.

![](/images/meat_prices/ikon.png)

In the *opinion* section of Ikon.mn. Headline translation: “The price of meat is skyrocketing and there is a shortage!”

Here is a rough generalization of the behavior of herders. This, of course, does not speak for all herders but from what I have observed this is relatively typical behavior. In the Fall before winter sets in herders will slaughter or sell those animals which are likely to die in the coming winter. Then in the Spring during breeding season herders often restrict the amount they sell so as not to limit their potential growth that year. In the Summer the productive animals are known and herders are more willing to sell or slaughter those animals that are not pregnant.

With this cycle, it is clear that seasonal prices are primarily being driven by the supply of meat. Prices go down in the Fall, hit the bottom in the Winter, and then rise dramatically in the Spring, reaching the peak in the Summer.

To ensure the supply of meat, the government purchases extra meat when prices are generally low and freeze it for use in times when supply is lower. This program has been going on for several years and the Minister of Food, Agriculture, and Light Industry [recently stated they will increase the supply of this reserve meat on the market](https://ikon.mn/n/1ko9). However, based on available data it is not clear whether this program actually works or does not. This reserve meat is frozen for several months and, from what I have observed, is much less desirable in the market.

### Are increasing exports causing record prices?

Now that we have a short introduction to how the market works in Mongolia, let’s take a look at the factor most are blaming for the price increases, **exports**. Recently I was interview on [MNB World](https://www.facebook.com/mnbworld)’s weekly news program. Through this, I learned of the concern that international traders (particularly from China) are being blamed for buying meat in bulk, thus causing a meat shortage and prices to rise.

To understand this better I wanted to see if meat prices correlated with exports. After all, meat exports are not a new thing in Mongolia. If these exports were causing a fluctuation in the price of meat we should see these correlations. So let’s take a look!

![](/images/meat_prices/exports_rising.png)

The blue shaded bar chart is animal product exports (in tons), and the two lines are beef and mutton prices (all prices in this article are Ulaanbaatar averages). As the chart title says, the connection isn’t clear. Export rose dramatically in 2017 and 2018. There may be a lag where 2017 exports impact prices in 2018 and 2018 exports impact prices in 2019, but this doesn’t make too much sense (meat goes bad after a few months being frozen).

In 2017 exports more than doubled from 2016, but average meat prices actually went down. We do see another dramatic increase in exports in 2018, but prices reached the same high from 2015. Simply put, exports may be causing prices to increase, but I do not believe it is the main driver.

> Exports may be causing prices to increase, but I do not believe it is the main driver.

### 3.8% loss in 2018

There wasn’t much talk of dzud last winter. In fact, international NGO’s barely mentioned the fact that last year saw more adult animals die than any year since 2010. A total of 2.6 million adult animals were lost in 2018. Let’s visualize the adult animal loss and meat price.

![](/images/meat_prices/animal_losses.png)

In 2010 over 10 million adult animals died. [It was the last major dzud](https://en.wikipedia.org/wiki/Zud). Late 2010 then saw a dramatic rise in prices. I’m still unsure why we didn’t see a fast rise in prices. This was the same year Ulaanbaatar saw an explosion of people moving to the city. Perhaps them selling their herds caused a long enough increase in the supply to delay the rising prices.

Nevertheless, the large number of animals lost in 2018 is a very likely explanation for rising prices this Spring. Most likely both are responsible, as well as other external factors like **rising salaries** or **fuel prices**.

### What happened to inflation?

Since 2010, the consumer price index (CPI) [has gone up 84%](http://www.1212.mn/tables.aspx?tbl_id=DT_NSO_0600_001V2&CPI_001_select_all=0&CPI_001SingleSelect=_1&YearM_select_all=1&YearMSingleSelect=&viewtype=linechart). Annual inflation is somewhere between 6–9%. Given these numbers, it only makes sense that prices would go up. Yet since 2011 meat prices have been remarkably stable.

To illustrate this I took the monthly change in CPI from MongolBank and calculated _what_ _meat prices would be if they tracked inflation_.

![](/images/meat_prices/beef.png)

![](/images/meat_prices/mutton.png)

From 2012 to 2015 both mutton and beef trended above inflation. Then from 2016 to 2018 mutton was below inflation, with beef above. Now we see both again trending above the calculated inflation. What we can learn from this is that rising meat prices are not unexpected.

Prices go up because of inflation. If they don’t go up, but the currency value is decreasing due to inflation, that meat the _real price_ of meat actually _went down_ since 2012 when there was a large spike. This increase in price could simply be a reversion to the inflation trend that you would expect.

### Mongolians are richer than they were 8 years ago

Also, let’s remember that since 2010 wages have also increased quite a bit. In 2010 the average monthly wage was 345,000 MNT in Ulaanbaatar. In 2018 it was 1,119,700 MNT. That is an increase of 225%!

Given the currently rising meat prices, do you think that the amount of money the average person spends on meat has gone up since 2011?

![](/images/meat_prices/meat_income.png)

If you said yes, think again! Let’s assume that an ‘average’ person in Ulaanbaatar (making an average salary) has a family of three and each person eats 250 grams of meat per day (this is equivalent to the average US meat consumption per person in 2018) for a total of 750 grams of consumption for the family. Based on these assumptions we saw a reduction of around 7% for both mutton and beef as a percent of the average salary spent on meat.

#### The Tsuivan Index

To better understand the inflation of prices since 2011, I wanted to see how the price of other common items and service has changed. The [National Statistics Office of Mongolia](http://www.en.nso.mn/) (NSO) has recorded the average price of common goods and services going back to December 2010. Below, I’ve created an index for a selection of goods and services by setting the December 2010 price as 100. If prices increase or decrease it will show as a proportion of the December 2010 price (i.e. 100). In this way, you can effectively see the _percent change_ in prices since December 2010.

![](/images/meat_prices/haircuts.png)

From the above chart, you can see that beef is about 250% more expensive (2.5 times) than in December 2010. Mutton is about 240% more expensive. What is interesting is the increase in prices for the other items. Here is a description of each:

-   Restaurant Gulyash — This is the price of a typical goulash meal (including potato salad and tea) in Ulaanbaatar at a typical restaurant.
-   Tsuivan — This is the price of a plate of Tsuivan (including milk tea) at a ‘tsainii gazar’, which is a canteen style of food establishment common across Mongolia.
-   Men Haircut — The price of a men's haircut in Ulaanbaatar.
-   Women's Haircut — The price for a ‘simple’ women's haircut in Ulaanbaatar. For obvious reasons, they don’t track more complicated haircuts.

The most shocking price increases were for haircuts. Haircutting is a service business, and there is little in the way of materials needed other than the expertise of the person. In addition, haircuts are not imported and could be said to be a “Mongolian” product.

Of course, haircuts are of course not as necessary as meat for the average person, and haircuts can be performed at home. Other products like chips, Coca Cola, and other packaged foods aren’t tracked by the NSO, but based on my observations since 2012, they have increased significantly in price.

### Becoming the Meat Price Prophet

I’m not a big fan of time series forecasts. They are generally too general and not accurate enough to truly understand a problem. I’ve written about time series forecasting a few times in the past. Both times ([USD-MNT exchange rate](https://medium.com/mongolian-data-stories/forecasting-usd-mnt-exchange-rate-part-1-prophet-4e95ecadf9b2) and [MSE stocks](https://medium.com/mongolian-data-stories/using-facebooks-prophet-to-predict-mongolian-stocks-cdf4feabd558)) didn’t give good results. But it seems that for meat prices it might not be too bad! Or is it?

Back in November 2018, I used [Facebook’s Open Source Prophet](https://research.fb.com/prophet-forecasting-at-scale/) library to forecast mutton and beef prices (as a bonus on the USD-MNT exchange rate article). For reference (and to show the limitations of time series forecasts), here are the forecasts.

![](/images/meat_prices/feed_forecast.png)

![](/images/meat_prices/mutton_forecast.png)

Based on these forecasts our predictions were quite a bit off. But these forecasts don’t take into consideration animal losses, exports, or anything other than the seasonal trends.

Prophet allows the addition of ‘regressors’, which are simply other variables that impact the prediction. What I did this time was take the previous years animal loss and added it to the model. In addition, I took the average yearly loss since 2011 (1.1 million animals) and assumed that would be the animal loss for the next two years. Here is the output of these two models, one for mutton and one for beef. I chose not to forecast other meat types as beef and mutton are by far the most popular.

![](/images/meat_prices/forecast.png)

![](/images/meat_prices/forecast1.png)

For each one the blue line is the average forecast, the black dots are the actual average prices, and the blue shaded area is the 80% confidence interval. The short story is that the peak price is almost over and _we should expect a reduction in prices in June_.

I expect that these forecasts are more accurate than my previous ones because it includes one of the primary drivers of price, animal loss. However, it will be important to add additional features if you wanted to get a more accurate forecast.

### Conclusion

Intelligence agents “inspected” meat exporters. I assume they found meat.

Last week the General Intelligence Agency (equivalent to the FBI in the US) [conducted a search](https://ikon.mn/n/1ks5) of meat exporters warehouses. This implies there may be some conspiracy to raise meat prices or that exporters are hoarding meat to then sell back later at higher prices. This seems pretty ridiculous on the face of it.

Meat frozen more than a week is very undesirable on the market in Mongolia, and generally is offered at a much lower price. The Ministry of Food, Agriculture, and Light Industry say that their reserve meat is designed to provide a lower cost option for low-income families. This reserve meat is bought when prices are low (the Fall) and then sold in the Spring. This is not the first choice for any family. In most food markets in Ulaanbaatar, you buy meat that has been slaughtered that day.

Mongolia’s meat prices are a function it’s nomadic supply. Regulating meat prices would only hurt the nearly 30% of the country that is engaged in herding work. These herders also don’t have a large household income compared to Ulaanbaatar. Rising meat prices means more money in their pocket.

There is one question that hasn’t been discussed much. Who is hurt by rising meat prices? Low-income households have government reserve meat as an option. Average and upper-income households (assuming consistent consumption) spend a smaller portion of their income on meat compared to 2010. Let’s not forget that more meat exports contribute to the stability of the Tugrik and help diversify Mongolia’s economy so it isn’t so reliant on mining. Do you want Mongolia to be called Minegolia or Meatgolia?