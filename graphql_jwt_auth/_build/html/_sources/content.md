How do we best utilize the data we have?
=======================

In the interest of defining next steps with the above question in mind, much of the following input can be cross-referenced using [this book](https://drive.google.com/file/d/15Na-_a1V1D9EvZkDkoxZY3KUkFcC6_nS/view?usp=sharing) -- *Text Analysis with Python*. Additionally, the structure of the following pages was borrowed from the last slide of Poonam and Divya's presentation:

![](./_build/html/_images/Capture.PNG)

Having successfully parsed and pre-processed user hashtags, we are now equipped to conduct **text similarity analysis**. As Monir has repeatedly pointed out, Cosine Similarity is one way of measuring term/document similarity. Regardless of whether or not we chose that metric or another (i.e., Hamming, Manhattan, or Levenshtein Distance), as Martin's colleague pointed out, it's all just differences in word representations being expressed as Euclidian distance in vector space (which machine learning can glean insights from, even if they are the wrong ones).
