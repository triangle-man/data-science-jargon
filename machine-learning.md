# Machine learning

There seem to be two definitions, similar but not quite the same.

In the first, what is being learned is an ability to perform a specific task, usually one of *prediction*. In this sense, machine learning is *the study of computer programs whose proficiency on some task improves with experience.*

In the second definition, what is being learned is something about the way world is. In this sense, machine learning is *the study of computer programs that use the result of observation to reduce their uncertainty about the state of the world.*
   
Both definitions are perhaps too provocative: one tends to imagine much more intelligence than is usually going on.
   
The definitions are clearly related: if one knows how the world is, one can make predictions; conversely, if one can make successful predictions, then one could be said to have some knowledge of how the world is.
   
*Example:* My phone predicts the word I am typing so that I may complete the rest of the word with a single tap. If the prediction is wrong, so that I end up typing a different word, the word I actually typed is remembered and may be suggested next time in preference to the built-in guess. In this way the phone "learns" about the words I use and its performance on the task of predicting my word improves (at least, so long as I tend to write the same word).

*Example:* Many companies would like to predict, part way through the year, what their annual spend will be at the end of the year. Here is a possible algorithm: compute the "run rate" spending (that is, how much you are spending per month), and then assume this is what you will spend for the rest of the year. This prediction tends to improve through the year because more is known about what has been spent and how much things are costing.
   
*Example:* To get better at throwing darts, throw lots of darts, always trying to hit the bullseye. If you find that most of your darts have gone, say, left of the bullseye, adjust the point you are aiming at to be right of the bullseye by the same amount.
   
*Example:* To predict whether your flight will be delayed, compute the average Delay of all flights with the same carrier, from the same airport, at around the same time of day over the last few months. Use that as a prediction for your
delay.
   
*Example:* One in 1000 people has disease X. A test for disease X is available but it is imperfect: for both people with disease X and people without, the test is accurate 9 times out of 10. I have tested positive for disease X and I would like to know the chance that I actually do have disease X. In this example, I was in a state of ignorance before the test; specifically, there was a chance of 1 in 1000 that I had the disease. I have subsequently acquired some experience (the test was positive) and I would like to know what I know now.

For examples of more sophisticated techniques, see also: **neural networks**, **deep learning**, **inference**, **regression**, **modelling**.
  
For examples of different kinds of learning, see also: **supervised learning**, **unsupervised learning**, and **reinforcement learning**.


## TODO 

- Outline the history of subject
- Explain the difference with statistics


