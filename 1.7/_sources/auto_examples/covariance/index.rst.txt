

.. _sphx_glr_auto_examples_covariance:

.. _covariance_examples:

Covariance estimation
---------------------

Examples concerning the :mod:`sklearn.covariance` module.



.. raw:: html

    <div class="sphx-glr-thumbnails">

.. thumbnail-parent-div-open

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="The usual covariance maximum likelihood estimate can be regularized using shrinkage. Ledoit and Wolf proposed a close formula to compute the asymptotically optimal shrinkage parameter (minimizing a MSE criterion), yielding the Ledoit-Wolf covariance estimate.">

.. only:: html

  .. image:: /auto_examples/covariance/images/thumb/sphx_glr_plot_lw_vs_oas_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_covariance_plot_lw_vs_oas.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Ledoit-Wolf vs OAS estimation</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example shows covariance estimation with Mahalanobis distances on Gaussian distributed data.">

.. only:: html

  .. image:: /auto_examples/covariance/images/thumb/sphx_glr_plot_mahalanobis_distances_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_covariance_plot_mahalanobis_distances.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Robust covariance estimation and Mahalanobis distances relevance</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="The usual covariance maximum likelihood estimate is very sensitive to the presence of outliers in the data set. In such a case, it would be better to use a robust estimator of covariance to guarantee that the estimation is resistant to &quot;erroneous&quot; observations in the data set. [1]_, [2]_">

.. only:: html

  .. image:: /auto_examples/covariance/images/thumb/sphx_glr_plot_robust_vs_empirical_covariance_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_covariance_plot_robust_vs_empirical_covariance.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Robust vs Empirical covariance estimate</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="When working with covariance estimation, the usual approach is to use a maximum likelihood estimator, such as the EmpiricalCovariance. It is unbiased, i.e. it converges to the true (population) covariance when given many observations. However, it can also be beneficial to regularize it, in order to reduce its variance; this, in turn, introduces some bias. This example illustrates the simple regularization used in shrunk_covariance estimators. In particular, it focuses on how to set the amount of regularization, i.e. how to choose the bias-variance trade-off.">

.. only:: html

  .. image:: /auto_examples/covariance/images/thumb/sphx_glr_plot_covariance_estimation_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_covariance_plot_covariance_estimation.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Shrinkage covariance estimation: LedoitWolf vs OAS and max-likelihood</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Using the GraphicalLasso estimator to learn a covariance and sparse precision from a small number of samples.">

.. only:: html

  .. image:: /auto_examples/covariance/images/thumb/sphx_glr_plot_sparse_cov_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_covariance_plot_sparse_cov.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Sparse inverse covariance estimation</div>
    </div>


.. thumbnail-parent-div-close

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/covariance/plot_lw_vs_oas
   /auto_examples/covariance/plot_mahalanobis_distances
   /auto_examples/covariance/plot_robust_vs_empirical_covariance
   /auto_examples/covariance/plot_covariance_estimation
   /auto_examples/covariance/plot_sparse_cov

