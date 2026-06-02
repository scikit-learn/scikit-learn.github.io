

.. _sphx_glr_auto_examples_compose:

.. _compose_examples:

Pipelines and composite estimators
----------------------------------

Examples of how to compose transformers and pipelines from other estimators. See the :ref:`User Guide <combining_estimators>`.



.. raw:: html

    <div class="sphx-glr-thumbnails">

.. thumbnail-parent-div-open

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Datasets can often contain components that require different feature extraction and processing pipelines. This scenario might occur when:">

.. only:: html

  .. image:: /auto_examples/compose/images/thumb/sphx_glr_plot_column_transformer_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_compose_plot_column_transformer.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Column Transformer with Heterogeneous Data Sources</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example illustrates how to apply different preprocessing and feature extraction pipelines to different subsets of features, using ColumnTransformer. This is particularly handy for the case of datasets that contain heterogeneous data types, since we may want to scale the numeric features and one-hot encode the categorical ones.">

.. only:: html

  .. image:: /auto_examples/compose/images/thumb/sphx_glr_plot_column_transformer_mixed_types_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_compose_plot_column_transformer_mixed_types.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Column Transformer with Mixed Types</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="In many real-world examples, there are many ways to extract features from a dataset. Often it is beneficial to combine several methods to obtain good performance. This example shows how to use FeatureUnion to combine features obtained by PCA and univariate selection.">

.. only:: html

  .. image:: /auto_examples/compose/images/thumb/sphx_glr_plot_feature_union_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_compose_plot_feature_union.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Concatenating multiple feature extraction methods</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="In this example, we give an overview of TransformedTargetRegressor. We use two examples to illustrate the benefit of transforming the targets before learning a linear regression model. The first example uses synthetic data while the second example is based on the Ames housing data set.">

.. only:: html

  .. image:: /auto_examples/compose/images/thumb/sphx_glr_plot_transformed_target_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_compose_plot_transformed_target.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Effect of transforming the targets in regression model</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="The PCA does an unsupervised dimensionality reduction, while the logistic regression does the prediction.">

.. only:: html

  .. image:: /auto_examples/compose/images/thumb/sphx_glr_plot_digits_pipe_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_compose_plot_digits_pipe.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Pipelining: chaining a PCA and a logistic regression</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example constructs a pipeline that does dimensionality reduction followed by prediction with a support vector classifier. It demonstrates the use of GridSearchCV and Pipeline to optimize over different classes of estimators in a single CV run -- unsupervised PCA and NMF dimensionality reductions are compared to univariate feature selection during the grid search.">

.. only:: html

  .. image:: /auto_examples/compose/images/thumb/sphx_glr_plot_compare_reduction_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_compose_plot_compare_reduction.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Selecting dimensionality reduction with Pipeline and GridSearchCV</div>
    </div>


.. thumbnail-parent-div-close

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/compose/plot_column_transformer
   /auto_examples/compose/plot_column_transformer_mixed_types
   /auto_examples/compose/plot_feature_union
   /auto_examples/compose/plot_transformed_target
   /auto_examples/compose/plot_digits_pipe
   /auto_examples/compose/plot_compare_reduction

