**Updated on 11 May 2020**
## Heroku
This is section for describing Heroku service for free tier.


## Deploying
Deploying in this platform isn't hard.You can just make a connection to your project repository on your github account and that's it.
Or if you not want github,you can just add heroku as an upstream remote on your git.
Or you may want to install Heroku CLI for more friendly deploying your application.

> NOTE: Please to make cofiguration for your preferred programming
> language.Respect to Heroku docs,there will be have most of your
> programming language.

Links: [Heroku Docs](https://devcenter.heroku.com/)

## Restriction
As you choose free tier,there will be have some restriction.Some restriction may be freed if you providing your credit card.But if not,you have more restriction

1. Restriction you have, just 1000 dyno hours or equivalent as 1000 real hours,or 41 Days non stop per month per account
2. Your application will paused if in 30 minutes not have a visitor.**See trick section if you want tou get rid of this**

**Have a Credit Card?**
1. You are eligible for free tier,but you must watch your usage.
2. Free tier in this scope you can change app url to your own custom domain **Must Have a Domain**
3. Free tier can install heroku add-on such as monitoring your application,database.

**Not Have a Credit Card?**
Not have a credit card you almost have all feature the free tier offer.But you are not eligible for feature on **'have a credit card'**

## Tricks
30 minutes inactive lead your application to be shutting down,and if new visitor visit your application,visitor may encounter slow response. 

So to get rid of this you can just make a **cronjob** or **schedule job** or something else.Or if you have verified account (Have entered credit card information) you can use New Relic add-on [New Relic](https://elements.heroku.com/addons/newrelic)

