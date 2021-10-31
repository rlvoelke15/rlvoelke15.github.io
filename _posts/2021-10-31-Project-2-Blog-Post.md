ST 558 Blog Post Project 2
================

## Prompt

PROMPT:
.	Outline your project and reflect on the process - What would you do differently? What was the most difficult part for you? 
.	What are you big takeaways from this project?

## Relevant Links

Link to Project 2 Github Pages README (Incl. Links to Each Channel Analysis):
<https://kafrazi2.github.io/Project-2/>

Link to ST 558 Project 2 Repo:
<https://github.com/kafrazi2/Project-2/tree/main>

## Blog Post

For this Project Assignment, we automated an analysis of content (i.e. Online Articles) across 6 different data channels, to predict the number of shares as a function of a variety of variables. We built multiple, linear models, as well as a Random Forest Model and Boosted Tree Model. We then fit the models to our test data and compared Root Mean Square Errors (RMSEs) across each model. For each data channel, the model with the lowest RMSE should be used to predict shares as a function of the listed predictor variables.

I think the most difficult part was understanding the logic / benefit behind the Boosted Tree Model and how to most efficiently select the parameters to use in the Boosted Tree Model. It felt a bit random to me at first, plugging in n.trees and shrinkage parameters, etc. However, via Cross Validation, you can compare the RMSEs of each of the Boosted Tree Models being output. I think I learned, as a part of this Project (and this entire Section 3) how important it is to understand the statistics and the reasoning behind each of the modeling options and when you might use each one. Knowing the formula syntax and R Code alone, isn't enough as you get deeper into your analysis! 

If I could do one thing differently, I would have spent more time at the onset of project focusing on the project as a whole, and not just focusing on the 'silo'ed sections that were assigned to myself in the instructions. This leads to my biggest takeaway, which is the importance of communication! My partner and I were able to regularly and openly communicate on what we were doing. While there were explicitly prescribed assignments between Partner 1 and Partner 2 in the instructions, we both made a conscious effort to still be engaged and involved in what the other was doing as we worked, and were available to help, if either of us ever got stuck. 

Overall, I enjoyed this process and being able to further build and expand my skill set within R and focusing our application on statistical analyses!

