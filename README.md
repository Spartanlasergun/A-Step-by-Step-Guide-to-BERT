# A Step by Step Guide To BERT

This repository contains a step by step guide to using the BERT model for text classification. A dataset of tweets for positive and negative sentiment classification is utilizied, as positive/negative sentiment classification is one of the more interesting areas of machine learning that is applicable at a reasonably lower level.

This guide has been created with the intention of making machine learning more accessible to the persons diving into the area for the first time - though, the complexity of machine learning inevitably makes it better suited as a resource for users that are already familiar with statistics and python. Still, I have kept the guide simple enough that most beginner programmers will still be able to make a lot of headway with understanding and using the BERT model. My recommendation is that the person using this guide should read through it very slowly. Attempt to understand the code in each cell along with the explanations given before moving forward.

It is very difficult to avoid touching on advanced topics in statistics and taking other concepts for granted. In particular I have avoided going into detail on explanations of logistic regression which would only serve to complicate things unnecessarily.

The google collaboratory notebook - 'A_Step_by_Step_Guide_To_BERT.ipynb' - gives a complete step by step walkthrough of:
* loading data
* doing the preprocessing
* intializing the bert model
* generating the embeddings
* and, performing text classification using logistic regression

The dataset used for the walktrough is contained in the file 'data.csv'.

-----
### Other Resources

If you wish to explore machine learning in a more in depth manner, you can consult the following resources:
* Getting Started with Goole BERT - by Sudharsan Ravichandiran
* Transformers for natural language processing - by Denis Rothman
* What is ChatGPT doing...and why does it work - by Stephen Wolfram

If you are a more advanced user and you want to understand the priniciples of logistic regression itself, you can consult:
* Logistic Regression: A Self Learning Text - by David Kleinbaum & Mitchel Klein
