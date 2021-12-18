# L1L2pack Introduction

L1L2pack contains classes and methods for L1 and L2 regularisation in statistical learning, and an initial version will be put here sometime in 2022.  It provides a library of LASSO and penalised estimation methods, and methods specific to time series prediction (e.g. cross validation via moving windows) and multivariate time series along with executables.  

All statistical methods in L1L2pack are programmed using the  [Eigen](https://eigen.tuxfamily.org/index.php?title=Main_Page) library, and OpenMP is utilised in methods where a regularisation step is repeated a large number of times (e.g. for bootstrapping and CV).

Examples of methods supported include:

LASSO<br>
Group LASSO<br>
Sparse Additive Models (SPAM)<br>
Random LASSO (Wang et al., 2011, Journal of Applied Statistics)<br>

.
