# A Theoretical Comparisons Between LIME and SHAP
In this project, I compared (linear) LIME and SHAP in three properties below:
- Local Accuracy
- Missingness
- Consistency

According to [SHAP paper](https://arxiv.org/abs/1705.07874), LIME fails to hold the above properties when its parameters are chosen heuristically. 

I experimented with various kernel functions and kernel width on the [LIME algorithm for image classifier model](https://marcotcr.github.io/lime/tutorials/Tutorial%20-%20images.html), observed that LIME fails in some extreme cases of kernel width (no noticable difference for different choice of kernels). 

The code is presented in [Jupyter Notebook](https://github.com/lizruonan/limeproject/blob/main/lime_modify_kernel.ipynb).

The formal proof of the failure of LIME is presented in the appendix of my [report](https://github.com/lizruonan/limeproject/blob/main/Machine_Learning_Fall_2019_Final_Project.pdf). 
