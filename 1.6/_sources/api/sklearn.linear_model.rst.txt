:html_theme.sidebar_secondary.remove:


.. _linear_model_ref:


sklearn.linear_model
====================

.. automodule:: sklearn.linear_model


**User guide.** See the :ref:`linear_model` section for further details.

The following subsections are only rough guidelines: the same estimator can fall into multiple categories, depending on its parameters.




.. _linear_model_ref-linear-classifiers:



Linear classifiers
------------------




.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  LogisticRegression
  LogisticRegressionCV
  PassiveAggressiveClassifier
  Perceptron
  RidgeClassifier
  RidgeClassifierCV
  SGDClassifier
  SGDOneClassSVM


.. _linear_model_ref-classical-linear-regressors:



Classical linear regressors
---------------------------




.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  LinearRegression
  Ridge
  RidgeCV
  SGDRegressor


.. _linear_model_ref-regressors-with-variable-selection:



Regressors with variable selection
----------------------------------



The following estimators have built-in variable selection fitting procedures, but any estimator using a L1 or elastic-net penalty also performs variable selection: typically :class:`~linear_model.SGDRegressor` or :class:`~sklearn.linear_model.SGDClassifier` with an appropriate penalty.


.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  ElasticNet
  ElasticNetCV
  Lars
  LarsCV
  Lasso
  LassoCV
  LassoLars
  LassoLarsCV
  LassoLarsIC
  OrthogonalMatchingPursuit
  OrthogonalMatchingPursuitCV


.. _linear_model_ref-bayesian-regressors:



Bayesian regressors
-------------------




.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  ARDRegression
  BayesianRidge


.. _linear_model_ref-multi-task-linear-regressors-with-variable-selection:



Multi-task linear regressors with variable selection
----------------------------------------------------



These estimators fit multiple regression problems (or tasks) jointly, while inducing sparse coefficients. While the inferred coefficients may differ between the tasks, they are constrained to agree on the features that are selected (non-zero coefficients).


.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  MultiTaskElasticNet
  MultiTaskElasticNetCV
  MultiTaskLasso
  MultiTaskLassoCV


.. _linear_model_ref-outlier-robust-regressors:



Outlier-robust regressors
-------------------------



Any estimator using the Huber loss would also be robust to outliers, e.g., :class:`~linear_model.SGDRegressor` with ``loss='huber'``.


.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  HuberRegressor
  QuantileRegressor
  RANSACRegressor
  TheilSenRegressor


.. _linear_model_ref-generalized-linear-models-(glm)-for-regression:



Generalized linear models (GLM) for regression
----------------------------------------------



These models allow for response variables to have error distributions other than a normal distribution.


.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  GammaRegressor
  PoissonRegressor
  TweedieRegressor


.. _linear_model_ref-miscellaneous:



Miscellaneous
-------------




.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  PassiveAggressiveRegressor
  enet_path
  lars_path
  lars_path_gram
  lasso_path
  orthogonal_mp
  orthogonal_mp_gram
  ridge_regression
