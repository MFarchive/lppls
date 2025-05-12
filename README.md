# lppls
Machine Learning Stock Bubble Identifier (LPPLS model)

This project aims to showcase my code of a machine learning algorithm which identifies stock market bubbles.
The algorithm uses k-means clustering and other techniques to identify if a tradeable equity stock is in a positive or negative unsustainable bubble.

Rough methodology:
Bubbles are assumed to reach a peak (or trough) after which they will collapse.
Looking at historical data bubbles can be predicted.
By fitting a lppls (log-periodic power law singularity) model to multiple windows of historic price data, bubbles can be predicted with a variable confidence.
K-means clustering is used to group predictions into likely estimates for the bubble peak time.
Also outputted are the bubble sizes (peak price), time to the bubble, and bubble likelihoods.
