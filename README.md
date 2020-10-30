# A Theoretical Comparisons Between LIME and SHAP
In this project, I compared (linear) LIME and SHAP with three properties:
- Local Accuracy
- Missingness
- Consistency
According to [SHAP paper](https://arxiv.org/abs/1705.07874), LIME fails to hold the above properties when its parameters are chosen heuristically. 
I experimented with different kernels and kernel widths on the [LIME algorithm for image classifier model](https://marcotcr.github.io/lime/tutorials/Tutorial%20-%20images.html), observed that LIME fails in some extreme cases of kernel width (no noticable difference between different choice of kernels). 
The mathematical proof of the failure of LIME caused by extreme case of kernel width can be viewed in the PDF file. 
