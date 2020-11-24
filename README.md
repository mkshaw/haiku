# haiku

There is an account/
Called accidental 5 7/
5. Let's copy it.

<a href="https://twitter.com/accidental575?lang=en" target="_blank">Accidental 575</a> is a Twitter feed of cultivated accidental haikus; a bot finds (/found, it seems to have been retired) accidental haikus in Tweets, and the bot owner Tweeted their favourites. This process involves scraping and then analyzing syllable structure. The goal is to re-create the haiku bot, to get experience with (a) scraping, (b) NLP/computational linguistics, and (c) whimsy.

Step 1: download random data from Twitter API (or data from a subset of celebrities, maybe 300 most-followed accounts?): https://developer.twitter.com/en/docs

Step 2: explore what data the API returns

Step 3: get the Tweet content (excluding quoted content in a quote-Tweet, but including caption) and conduct syllable analysis: https://github.com/prosegrinder/python-cmudict
