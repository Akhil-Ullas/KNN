📌 What is K-Nearest Neighbors and What Does It Do?
K-Nearest Neighbors is a non-parametric, instance-based learning algorithm that makes predictions by comparing a new data point to its K closest neighbors in the feature space.

Predictions are made by:

Majority voting (classification)

Averaging neighbor values (regression)

Model behavior is influenced by:

value of K

distance metric

feature scaling

neighborhood density

Unlike model-based algorithms, KNN does not learn an explicit decision function — the dataset itself acts as the model.

✔ Advantages of KNN

Simple, intuitive, and easy to implement

Works well on small to medium-sized datasets

Naturally models non-linear boundaries

No explicit training phase

Useful as a strong baseline model

✘ Disadvantages of KNN

Computationally expensive during prediction

Highly sensitive to scaling and noise

Degrades in high-dimensional spaces

Requires careful K selection

Memory-intensive
