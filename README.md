# PolBotCheck
Check political bots on social networks

The goal is to show information about politicians regarding who is retweeting their Twitter
tweets, if it is humans or bots.

We use information from [Truthy BotOrNot](http://truthy.indiana.edu/botornot/), a project
from Indiana University, which calculates a probability of a Twitter account being a bot
or a human. We check that on retweeters of a politician and calculate a score for each
topic (aka hashtag) he or she is talking about. This helps to identify, if a tweet is
really interesting to the public or if it is only interesting for certain bots.


## Checkout and run

    get clone https://github.com/codeforfrankfurt/PolBotCheck.git
    cd PolBotCheck/web
    npm start
