:html_theme.sidebar_secondary.remove:


.. _metrics_ref:


sklearn.metrics
===============

.. automodule:: sklearn.metrics


**User guide.** See the :ref:`model_evaluation` and :ref:`metrics` sections for further details.




.. _metrics_ref-model-selection-interface:



Model selection interface
-------------------------



**User guide.** See the :ref:`scoring_parameter` section for further details.


.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  check_scoring
  get_scorer
  get_scorer_names
  make_scorer


.. _metrics_ref-classification-metrics:



Classification metrics
----------------------



**User guide.** See the :ref:`classification_metrics` section for further details.


.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  accuracy_score
  auc
  average_precision_score
  balanced_accuracy_score
  brier_score_loss
  class_likelihood_ratios
  classification_report
  cohen_kappa_score
  confusion_matrix
  d2_log_loss_score
  dcg_score
  det_curve
  f1_score
  fbeta_score
  hamming_loss
  hinge_loss
  jaccard_score
  log_loss
  matthews_corrcoef
  multilabel_confusion_matrix
  ndcg_score
  precision_recall_curve
  precision_recall_fscore_support
  precision_score
  recall_score
  roc_auc_score
  roc_curve
  top_k_accuracy_score
  zero_one_loss


.. _metrics_ref-regression-metrics:



Regression metrics
------------------



**User guide.** See the :ref:`regression_metrics` section for further details.


.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  d2_absolute_error_score
  d2_pinball_score
  d2_tweedie_score
  explained_variance_score
  max_error
  mean_absolute_error
  mean_absolute_percentage_error
  mean_gamma_deviance
  mean_pinball_loss
  mean_poisson_deviance
  mean_squared_error
  mean_squared_log_error
  mean_tweedie_deviance
  median_absolute_error
  r2_score
  root_mean_squared_error
  root_mean_squared_log_error


.. _metrics_ref-multilabel-ranking-metrics:



Multilabel ranking metrics
--------------------------



**User guide.** See the :ref:`multilabel_ranking_metrics` section for further details.


.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  coverage_error
  label_ranking_average_precision_score
  label_ranking_loss


.. _metrics_ref-clustering-metrics:



Clustering metrics
------------------



.. automodule:: sklearn.metrics.cluster

.. currentmodule:: sklearn.metrics

**User guide.** See the :ref:`clustering_evaluation` section for further details.


.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  adjusted_mutual_info_score
  adjusted_rand_score
  calinski_harabasz_score
  cluster.contingency_matrix
  cluster.pair_confusion_matrix
  completeness_score
  davies_bouldin_score
  fowlkes_mallows_score
  homogeneity_completeness_v_measure
  homogeneity_score
  mutual_info_score
  normalized_mutual_info_score
  rand_score
  silhouette_samples
  silhouette_score
  v_measure_score


.. _metrics_ref-biclustering-metrics:



Biclustering metrics
--------------------



**User guide.** See the :ref:`biclustering_evaluation` section for further details.


.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  consensus_score


.. _metrics_ref-distance-metrics:



Distance metrics
----------------




.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  DistanceMetric


.. _metrics_ref-pairwise-metrics:



Pairwise metrics
----------------



.. automodule:: sklearn.metrics.pairwise

.. currentmodule:: sklearn.metrics

**User guide.** See the :ref:`metrics` section for further details.


.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  pairwise.additive_chi2_kernel
  pairwise.chi2_kernel
  pairwise.cosine_distances
  pairwise.cosine_similarity
  pairwise.distance_metrics
  pairwise.euclidean_distances
  pairwise.haversine_distances
  pairwise.kernel_metrics
  pairwise.laplacian_kernel
  pairwise.linear_kernel
  pairwise.manhattan_distances
  pairwise.nan_euclidean_distances
  pairwise.paired_cosine_distances
  pairwise.paired_distances
  pairwise.paired_euclidean_distances
  pairwise.paired_manhattan_distances
  pairwise.pairwise_kernels
  pairwise.polynomial_kernel
  pairwise.rbf_kernel
  pairwise.sigmoid_kernel
  pairwise_distances
  pairwise_distances_argmin
  pairwise_distances_argmin_min
  pairwise_distances_chunked


.. _metrics_ref-plotting:



Plotting
--------



**User guide.** See the :ref:`visualizations` section for further details.


.. autosummary::
  :nosignatures:
  :toctree: ../modules/generated/
  :template: base.rst


  ConfusionMatrixDisplay
  DetCurveDisplay
  PrecisionRecallDisplay
  PredictionErrorDisplay
  RocCurveDisplay
