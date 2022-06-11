## Intro to analyzing Twitter data

![](https://try.dominodatalab.com/u/joshpoduska/twitter_NLP/raw/1f6653583c467e87e7bd332bdd6537abf5a67db3/results/%40poem_exe_WordCloud.png?inline=true)

## Follow the steps below before running the notebook for this project

1. ***FORK THE PORJECT***

2. Open [twitter.ipynb](view/twitter.ipynb) and click "Launch Notebook"

3. Follow the directions in the notebook

That's it! There is also a [blog post](https://blog.dominodatalab.com/------) <not live yet> associated with this project that offers additional background. 

---------------------------------------------------

## This project has sample data loaded. You can use that, or you can pull your own Twitter data from any account by leveraging your own Twiter API Keys and Tokens. See below for instructions.

Simply save your own Twitter keys and tokens to your Domino user profile. The following steps describe how to do this.

1. Get your Twitter keys and tokens

    a) Go to https://dev.twitter.com/apps/new and log in, if necessary
    
    b) Supply the necessary required fields, accept the Terms Of Service, and solve the CAPTCHA
    
    c) Submit the form
    
    d) Go to the API Keys tab, there you will find your Consumer key and Consumer secret keys
    
    e) Copy the consumer key (API key) and consumer secret from the screen into our application
    
    
2. Store the keys and tokens as "Domino User Environment Variables"

    a) Visit your "Account Settings" page
    
    b) Scroll down to the section titled "User environment variables"
    
    c) Create 4 variables named "TWITTER_CONSUMER_KEY", "TWITTER_CONSUMER_SECRET", "TWITTER_ACCESS_TOKEN", and "TWITTER_ACCESS_TOKEN_SECRET" with the associated keys and tokens stored in the variables

3. Open [twitter.ipynb](view/twitter.ipynb) and click "Launch Notebook"

4. Follow the directions in the notebook