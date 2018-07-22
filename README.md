# Social-Feedback-weight-loss-community

In this notebook we demonstrate the use of "matching" when using observational data to estimate the effect size of receiving a "treatment" vs. not receiving a treatment, i.e. being in the "control" group. The vast majority of this notebook has been put together by Tiago Cunha. https://sites.google.com/site/tiagocunha87/

In this concrete example we use real data from the Reddit community called "loseit", an online forum dedicated to weight loss. https://www.reddit.com/r/loseit/

We want to see if the treatment of receiving a "warm welcome" on one's first post in this subreddit has an effect on a user's probability to return for a second post in the future. Concretely, we look at the number of upvotes a post receives and define users whose first post on loseit did not receive a single upvote as the control group (see e.g. https://www.reddit.com/r/loseit/comments/o3h7y). Correspondingly, we define users whose first post received at least one upvote as the treatment group (see e.g. https://www.reddit.com/r/loseit/comments/238r4o).

The data we are using for this tutorial covers 37,279 users whose first post occurred between August 2010 to October 2014. The data was obtained by crawling Reddit using PRAW (http://praw.readthedocs.org), a Python package that allows simple access to Reddit's official API. For more details see the corresponding DigitalHealth'16 publication: Tiago Cunha, Ingmar Weber, Hamed Haddadi, Gisele Pappa: The Effect of Social Feedback in a Weight Loss Subreddit, preprint at http://arxiv.org/abs/1602.07936.
