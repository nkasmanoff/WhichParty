Which Party???
==============

This directory contains a model to try and classify political beliefs as either Democrat or Republican. 

The prototype plan is to train a natural language based RNN on political statements, stemming from campaign website (where that candidate stands on the issues), the political party platform, and other credible online resources that outline where the party stands on some particular topic. 

Once complete with training, the hope would be to input some new data serving as a questionable statement, perhaps a sanity check of "I believe in climate change and it should be addressed", a topic certainly more aligned with the Democratic platform and then confirm this model's validity, and then expanding this further to apply this research to a certain candidate's openly declared platform via their campaign website, and try to grade their stances on whether or not said candidate truly aligns with their proclaimed party, how central they are, or far right. More to come from here, but that's the initial idea. 


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




MODEL
------

As previously mentioned, this will be an RNN. 

I'll be roughly basing this model on the IMDB review dataset, which attempts to classify reviews on the imdb website as positive or negative. 
