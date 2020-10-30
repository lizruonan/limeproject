# A Theoretical Comparisons Between LIME and SHAP
In this project, I compared (linear) LIME and SHAP with three properties:
- Local Accuracy
- Missingness
- Consistency

According to [SHAP paper](https://arxiv.org/abs/1705.07874), LIME fails to hold the above properties when its parameters are chosen heuristically. 

I experimented with various kernel functions and kernel width on the [LIME algorithm for image classifier model](https://marcotcr.github.io/lime/tutorials/Tutorial%20-%20images.html), observed that LIME fails in some extreme cases of kernel width (no noticable difference for different choice of kernels). 

The formal proof of the failure of LIME is presented in the appendix of my PDF file. 
