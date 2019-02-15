# Standardize vs. Normalize

## 1. Normalization

### Definition

Normalization is often performed on data to remove amplitude variation and only focuses on the underlying distribution shape.

It is thus useful when comparing two datasets (statistical comparison).

What does **Normalization** do? 

* Normalization makes training less sensitive to the scale of features, so we can better solve for coefficients.
* Normalization makes the data better conditioned for convergence (avoid scaling issues).
* Normalizing will ensure that a convergence problem does not have a massive variance, making optimization feasible.

### Formula

$$
z = \frac{x - min(x)}{max(x) - min(x)}
$$

__z__ will now be  __0 $\le$ z $\le$ 1__

 ### Usage

Normalization is done along with several algorithms:

* K-means
* K-nearest neighbors
* Logistic Regression
* SVM
* Perceptron
* Linear Discriminant Analysis
* PCA
* Kernel Principal Component Analysis

Which algorithms don't need Normalization?

* Decision Tree

## 2. Standardization





### References

1. https://medium.com/@rrfd/standardize-or-normalize-examples-in-python-e3f174b65dfc
2. http://www.dataminingblog.com/standardization-vs-normalization/
3. https://www.quora.com/What-is-the-difference-between-normalization-standardization-and-regularization-for-data
4. http://www.faqs.org/faqs/ai-faq/neural-nets/part2/section-16.html