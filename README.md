# election-tweeter

#### simple python web scraper that utilizes the twitter api to tweet live election data
 
### usage:
####  - to use this program, clone the repo into a directory of your choice
####  - then, create a [twitter developer account](https://developer.twitter.com/en), and create a new app
####  - in the election.py file:

~~~
auth = tweepy.OAuthHandler("YOS0DjxdDN3JcVZWSM8fzlrOQ", "dAt2hhJgV5M06BiOPZRxxEtEnMU85oOWF1CN8tpD3xsFolfnmN")
auth.set_access_token("1046043340196761602-JILFVkGovrZgVXNXoJmqMz1yAbLydI", "CjYSI8CfilrWfdj4cBN3lEKxzT7eAkfdLdWnfhkHy9gL1")
~~~

####  - replace the strings in the code above with your own api and consumer keys and tokens (don't try to run it with my keys... i obviously regenerated them and these keys don't work anymore :))

####  - lastly, run the program either in an ide of your choice or in the command line:
~~~
python election.py
~~~

#### enjoy!


## About:
#### hi, i'm sid! to see my other projects, visit my [website](http://dev.siddharthlohani.ninja/)!
