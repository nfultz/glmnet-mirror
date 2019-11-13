
<!-- README.md is generated from the source: README.Rmd -->

# Lasso and Elastic-Net Regularized Generalized Linear Models

This is a patched version of glmnet that runs final fits
in parallel with k folds crossvalidation, and saves a full
copy of the data set per fold, allowing you to run roughly
twice as many folds in the same amount of memory.