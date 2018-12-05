Which Party???
==============

A natural language processing based classifier to distinguish between republican and democratic values. 

This directory contains a model to try and classify political beliefs as either Democrat or Republican. 

The plan is to train a natural language based RNN on political statements, stemming from campaign website (where that candidate stands on the issues), the political party platform, and other credible online resources that outline where the party stands on some particular topic. Such resources are either linked to in the python notebook, or also in the repo as rather large text documents. 

Once complete with training, the hope would be to input some new data serving as a questionable statement, perhaps a sanity check of "I believe in climate change and it should be addressed", a topic (sadly) more aligned with the Democratic platform. 

Expanding this further, I can in the future apply this research to a candidate's declared platform via their campaign website, and try to grade their stances on whether or not said candidate truly aligns with their proclaimed party, how central they are, right, left, etc. More to come from here, but that's the initial idea. I'll be working with.


As midterm season has come and past, I anticipate a motivation to get back on this project closer to 2020. 


DATA SOURCES
------------
(an ever growing list)


https://www.democrats.org/party-platform

https://www.gop.com/platform/ -- This one is split into further branches ugh, could probably do somethign with HTML to fix? 

https://betofortexas.com/issues/


http://www.ontheissues.org/Senate/Ted_Cruz.htm

ontheissues.org looks like it can do just about everyone. 


http://www.ontheissues.org/Democratic_Party.htm

http://www.ontheissues.org/Republican_Party.htm


New sources:

R

https://www.republicanviews.org/republican-views-on-the-economy/

https://www.republicanviews.org/republican-views-on-energy/

https://www.republicanviews.org/republican-views-on-the-environment/

https://www.republicanviews.org/republican-views-on-health-care/

https://www.republicanviews.org/republican-views-on-immigration/

https://www.republicanviews.org/republican-views-on-social-security/

https://www.republicanviews.org/republican-views-on-bitcoin-and-cryptocurrencies/

https://www.republicanviews.org/republican-views-on-the-u-s-embassy-in-jerusalem/

https://www.republicanviews.org/republican-views-on-unemployment/

https://www.republicanviews.org/republican-views-on-terrorism/

https://www.republicanviews.org/republican-views-on-stem-cell-research/

https://www.republicanviews.org/republican-views-on-the-electoral-college/

https://www.republicanviews.org/republican-views-on-religion/

https://www.republicanviews.org/republican-views-on-net-neutrality/


D

https://www.republicanviews.org/democratic-views-on-military-spending/

https://www.republicanviews.org/democratic-views-on-gay-marriage/

https://www.republicanviews.org/democratic-party-beliefs/

https://www.republicanviews.org/democratic-views-on-planned-parenthood/

https://www.republicanviews.org/democratic-views-on-foreign-policy/

https://www.republicanviews.org/democratic-views-on-illegal-immigration/

https://www.republicanviews.org/democratic-views-on-banking-regulation/

https://www.republicanviews.org/democratic-views-on-crime/


https://www.republicanviews.org/democratic-views-on-the-u-s-embassy-in-jerusalem/


https://www.republicanviews.org/democratic-views-on-trade/

https://www.republicanviews.org/democratic-views-on-energy/

https://www.republicanviews.org/democratic-views-on-national-security/

https://www.republicanviews.org/democratic-views-on-the-military/

MODEL USED
-----------

As previously mentioned, this will be an RNN. 

I'll be roughly basing this model on the IMDB 


