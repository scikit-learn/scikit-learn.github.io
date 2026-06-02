

.. _sphx_glr_auto_examples_preprocessing:

.. _preprocessing_examples:

Preprocessing
-------------

Examples concerning the :mod:`sklearn.preprocessing` module.



.. raw:: html

    <div class="sphx-glr-thumbnails">

.. thumbnail-parent-div-open

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Feature 0 (median income in a block) and feature 5 (average house occupancy) of the california_housing_dataset have very different scales and contain some very large outliers. These two characteristics lead to difficulties to visualize the data and, more importantly, they can degrade the predictive performance of many machine learning algorithms. Unscaled data can also slow down or even prevent the convergence of many gradient-based estimators.">

.. only:: html

  .. image:: /auto_examples/preprocessing/images/thumb/sphx_glr_plot_all_scaling_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_preprocessing_plot_all_scaling.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Compare the effect of different scalers on data with outliers</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="The TargetEncoder uses the value of the target to encode each categorical feature. In this example, we will compare three different approaches for handling categorical features: TargetEncoder, OrdinalEncoder, OneHotEncoder and dropping the category.">

.. only:: html

  .. image:: /auto_examples/preprocessing/images/thumb/sphx_glr_plot_target_encoder_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_preprocessing_plot_target_encoder.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Comparing Target Encoder with Other Encoders</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example presents the different strategies implemented in KBinsDiscretizer:">

.. only:: html

  .. image:: /auto_examples/preprocessing/images/thumb/sphx_glr_plot_discretization_strategies_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_preprocessing_plot_discretization_strategies.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Demonstrating the different strategies of KBinsDiscretizer</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="A demonstration of feature discretization on synthetic classification datasets. Feature discretization decomposes each feature into a set of bins, here equally distributed in width. The discrete values are then one-hot encoded, and given to a linear classifier. This preprocessing enables a non-linear behavior even though the classifier is linear.">

.. only:: html

  .. image:: /auto_examples/preprocessing/images/thumb/sphx_glr_plot_discretization_classification_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_preprocessing_plot_discretization_classification.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Feature discretization</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Feature scaling through standardization, also called Z-score normalization, is an important preprocessing step for many machine learning algorithms. It involves rescaling each feature such that it has a standard deviation of 1 and a mean of 0.">

.. only:: html

  .. image:: /auto_examples/preprocessing/images/thumb/sphx_glr_plot_scaling_importance_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_preprocessing_plot_scaling_importance.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Importance of Feature Scaling</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example demonstrates the use of the Box-Cox and Yeo-Johnson transforms through PowerTransformer to map data from various distributions to a normal distribution.">

.. only:: html

  .. image:: /auto_examples/preprocessing/images/thumb/sphx_glr_plot_map_data_to_normal_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_preprocessing_plot_map_data_to_normal.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Map data to a normal distribution</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="The TargetEncoder replaces each category of a categorical feature with the shrunk mean of the target variable for that category. This method is useful in cases where there is a strong relationship between the categorical feature and the target. To prevent overfitting, TargetEncoder.fit_transform uses an internal cross fitting scheme to encode the training data to be used by a downstream model. This scheme involves splitting the data into k folds and encoding each fold using the encodings learnt using the other k-1 folds. In this example, we demonstrate the importance of the cross fitting procedure to prevent overfitting.">

.. only:: html

  .. image:: /auto_examples/preprocessing/images/thumb/sphx_glr_plot_target_encoder_cross_val_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_preprocessing_plot_target_encoder_cross_val.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Target Encoder's Internal Cross fitting</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="The example compares prediction result of linear regression (linear model) and decision tree (tree based model) with and without discretization of real-valued features.">

.. only:: html

  .. image:: /auto_examples/preprocessing/images/thumb/sphx_glr_plot_discretization_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_preprocessing_plot_discretization.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Using KBinsDiscretizer to discretize continuous features</div>
    </div>


.. thumbnail-parent-div-close

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/preprocessing/plot_all_scaling
   /auto_examples/preprocessing/plot_target_encoder
   /auto_examples/preprocessing/plot_discretization_strategies
   /auto_examples/preprocessing/plot_discretization_classification
   /auto_examples/preprocessing/plot_scaling_importance
   /auto_examples/preprocessing/plot_map_data_to_normal
   /auto_examples/preprocessing/plot_target_encoder_cross_val
   /auto_examples/preprocessing/plot_discretization

