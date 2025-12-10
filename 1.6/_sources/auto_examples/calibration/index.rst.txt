

.. _sphx_glr_auto_examples_calibration:

.. _calibration_examples:

Calibration
-----------------------

Examples illustrating the calibration of predicted probabilities of classifiers.



.. raw:: html

    <div class="sphx-glr-thumbnails">

.. thumbnail-parent-div-open

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Well calibrated classifiers are probabilistic classifiers for which the output of predict_proba can be directly interpreted as a confidence level. For instance, a well calibrated (binary) classifier should classify the samples such that for the samples to which it gave a predict_proba value close to 0.8, approximately 80% actually belong to the positive class.">

.. only:: html

  .. image:: /auto_examples/calibration/images/thumb/sphx_glr_plot_compare_calibration_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_calibration_plot_compare_calibration.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Comparison of Calibration of Classifiers</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="When performing classification one often wants to predict not only the class label, but also the associated probability. This probability gives some kind of confidence on the prediction. This example demonstrates how to visualize how well calibrated the predicted probabilities are using calibration curves, also known as reliability diagrams. Calibration of an uncalibrated classifier will also be demonstrated.">

.. only:: html

  .. image:: /auto_examples/calibration/images/thumb/sphx_glr_plot_calibration_curve_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_calibration_plot_calibration_curve.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Probability Calibration curves</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example illustrates how sigmoid calibration changes predicted probabilities for a 3-class classification problem. Illustrated is the standard 2-simplex, where the three corners correspond to the three classes. Arrows point from the probability vectors predicted by an uncalibrated classifier to the probability vectors predicted by the same classifier after sigmoid calibration on a hold-out validation set. Colors indicate the true class of an instance (red: class 1, green: class 2, blue: class 3).">

.. only:: html

  .. image:: /auto_examples/calibration/images/thumb/sphx_glr_plot_calibration_multiclass_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_calibration_plot_calibration_multiclass.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Probability Calibration for 3-class classification</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="When performing classification you often want to predict not only the class label, but also the associated probability. This probability gives you some kind of confidence on the prediction. However, not all classifiers provide well-calibrated probabilities, some being over-confident while others being under-confident. Thus, a separate calibration of predicted probabilities is often desirable as a postprocessing. This example illustrates two different methods for this calibration and evaluates the quality of the returned probabilities using Brier&#x27;s score (see https://en.wikipedia.org/wiki/Brier_score).">

.. only:: html

  .. image:: /auto_examples/calibration/images/thumb/sphx_glr_plot_calibration_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_calibration_plot_calibration.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Probability calibration of classifiers</div>
    </div>


.. thumbnail-parent-div-close

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/calibration/plot_compare_calibration
   /auto_examples/calibration/plot_calibration_curve
   /auto_examples/calibration/plot_calibration_multiclass
   /auto_examples/calibration/plot_calibration

