Bechdel
=======

I tried to retrieve and re-analyze the data that Hickey described in his article, but came to some conclusions that were the same, others that were very different, and still others that I hope are new. 

In the absence of knowing the precise methods used but making reasnable assumptions of what was done, I was able to replicate some of his findings, but not others because specific decisions had to be made about the data or modeling that dramatically change the results of the statistical models. However, the article provides no specifics so we're left to wonder when and where these findings hold, which points to the need for openness in sharing data and code. Specifically, while Hickey found that women's representation in movies had no significant relationship on revenue, I found a positive and significant relationship. 

But the questions and hypotheses Hickey posed about systematic biases in Hollywood were also the right ones. With a reanalysis using different methods as well as adding in new data, I found statistically significant differences in popular ratings also exist. These differences persist after controlling for each other and in the face of other potential explanations about differences arising because of genres, MPAA ratings, time, and other effects.

In the image below, we see that movies that have non-trivial women's roles get 24% lower budgets, make 55% more revenue, get better reviews from critics, and face harsher criticism from IMDB users. Bars that are faded out mean my models are less confident about these findings being non-random (higher p-values) while bars that are darker mean my models are more confident that this is a significant finding (lower p-values).

Movies passing the Bechdel test (the red bars):

* ...receive budgets that are 24% *smaller*

* ...make 55% *more* revenue 

* ...are awarded 1.8 *more* Metacritic points by professional reviewers

* ...are awarded 0.12 *fewer* stars by IMDB's amateur reviewers

![Summary plot of Bechdel statistics](https://raw.githubusercontent.com/brianckeegan/Bechdel/master/Takeaway.png)
