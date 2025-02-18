# Changelog

## v0.2.2-dev

## v0.2.1 (2023-08-30)

### Enhancements

  * Remove `VegaLite.Data` in favour of future use of `Tucan`
  * Do not use EXLA at compile time in `Metrics`

## v0.2.0 (2023-08-29)

This version requires Elixir v1.14+.

### Enhancements

  * Update notebooks
  * Add support for `:f16` and `:bf16` types in `SVD`
  * Add `Affinity Propagation`
  * Add `t-SNE`
  * Add `Polynomial Regression`
  * Replace seeds with `Random.key`
  * Add 'unrolling loops' option 
  * Add support for custom optimizers in `Logistic Regression`
  * Add `Trapezoidal Integration`
  * Add `AUC-ROC`, `AUC`, and `ROC Curve`
  * Add `Simpson rule integration`
  * Unify tests
  * Add `Radius Nearest Neighbors`
  * Add `DBSCAN`
  * Add classification metrics: `Average Precision Score`, `Balanced Accuracy Score`,
  `Cohen Kappa Score`, `Brier Score Loss`, `Zero-One Loss`, `Top-k Accuracy Score`
  * Add regression metrics: `R2 Score`, `MSLE`, `MAPE`, `Maximum Residual Error`
  * Add support for axes in `Confusion Matrix`
  * Add support for broadcasting in `Metrics.Distances`
  * Update CI
  * Add `Gaussian Mixtures`
  * Add Model selection functionalities: `K-fold`, `K-fold Cross Validation`, `Grid Search`
  * Change structure of metrics in `Scholar`
  * Add a guide with `Cross-Validation` and `Grid Search`

## v0.1.0 (2023-03-29)

First release.
