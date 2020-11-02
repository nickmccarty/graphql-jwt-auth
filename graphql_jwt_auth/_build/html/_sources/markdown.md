How do we model hashtag association?
=======================

In the most general sense, we will want to isolate clusters of hashtags, whether it be temporally, topically, geographically, etc. In the absence of labeled training data, any worthwhile machine learning approaches would likely be unsupervised, as Martin's colleague pointed out. In that vein, K-Means would be the low-hanging fruit. Regardless, TF-IDF vectorization is certainly in order, vis a vis next steps.

[Some inspiration to get you started](https://smyachenkov.com/posts/categorizing-instagram-tags-with-k-means/).
