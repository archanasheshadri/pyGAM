
In comparison with linear models, 
- it has more flexibility because the relationship between independent and dependent variable are not assumed to be linear. We don't have to know a priori the type of predictive functions we will eventually need.



Source for this file: https://multithreaded.stitchfix.com/blog/2015/07/30/gam/

PROBLEM:
---------

We will be using a marketing example from the insurance industry (source undisclosed). The data contains information on customer responses to a historical direct mail marketing campaign. 
Our goal is to improve the performance of future waves of this campaign by targeting people who are likely to take the offer. We will do this by building a “look-alike” model to predict the probability that a given client will accept 
the offer, and then use that model to select the target audience going forward [1f].

Obviously, we want a model that is accurate so that we can find the best possible target audience. In addition, we want to be able to provide insights from the model, such as partial impact charts, 
that show how the average propensity changes across various client features. We want to make sure that the relationships we find stand to reason from a business perspective.

