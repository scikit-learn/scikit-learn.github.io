

.. _sphx_glr_auto_examples_svm:

.. _svm_examples:

Support Vector Machines
-----------------------

Examples concerning the :mod:`sklearn.svm` module.



.. raw:: html

    <div class="sphx-glr-thumbnails">

.. thumbnail-parent-div-open

.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="An example using a one-class SVM for novelty detection.">

.. only:: html

  .. image:: /auto_examples/svm/images/thumb/sphx_glr_plot_oneclass_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_svm_plot_oneclass.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">One-class SVM with non-linear kernel (RBF)</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="SVCs aim to find a hyperplane that effectively separates the classes in their training data by maximizing the margin between the outermost data points of each class. This is achieved by finding the best weight vector w that defines the decision boundary hyperplane and minimizes the sum of hinge losses for misclassified samples, as measured by the hinge_loss function. By default, regularization is applied with the parameter C=1, which allows for a certain degree of misclassification tolerance.">

.. only:: html

  .. image:: /auto_examples/svm/images/thumb/sphx_glr_plot_svm_kernels_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_svm_plot_svm_kernels.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Plot classification boundaries with different SVM Kernels</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Comparison of different linear SVM classifiers on a 2D projection of the iris dataset. We only consider the first 2 features of this dataset:">

.. only:: html

  .. image:: /auto_examples/svm/images/thumb/sphx_glr_plot_iris_svc_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_svm_plot_iris_svc.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Plot different SVM classifiers in the iris dataset</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Unlike SVC (based on LIBSVM), LinearSVC (based on LIBLINEAR) does not provide the support vectors. This example demonstrates how to obtain the support vectors in LinearSVC.">

.. only:: html

  .. image:: /auto_examples/svm/images/thumb/sphx_glr_plot_linearsvc_support_vectors_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_svm_plot_linearsvc_support_vectors.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Plot the support vectors in LinearSVC</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example illustrates the effect of the parameters gamma and C of the Radial Basis Function (RBF) kernel SVM.">

.. only:: html

  .. image:: /auto_examples/svm/images/thumb/sphx_glr_plot_rbf_parameters_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_svm_plot_rbf_parameters.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">RBF SVM parameters</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="A small value of C includes more/all the observations, allowing the margins to be calculated using all the data in the area.">

.. only:: html

  .. image:: /auto_examples/svm/images/thumb/sphx_glr_plot_svm_margin_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_svm_plot_svm_margin.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">SVM Margins Example</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="The two plots differ only in the area in the middle where the classes are tied. If break_ties=False, all input in that area would be classified as one class, whereas if break_ties=True, the tie-breaking mechanism will create a non-convex decision boundary in that area.">

.. only:: html

  .. image:: /auto_examples/svm/images/thumb/sphx_glr_plot_svm_tie_breaking_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_svm_plot_svm_tie_breaking.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">SVM Tie Breaking Example</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Simple usage of Support Vector Machines to classify a sample. It will plot the decision surface and the support vectors.">

.. only:: html

  .. image:: /auto_examples/svm/images/thumb/sphx_glr_plot_custom_kernel_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_svm_plot_custom_kernel.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">SVM with custom kernel</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="This example shows how to perform univariate feature selection before running a SVC (support vector classifier) to improve the classification scores. We use the iris dataset (4 features) and add 36 non-informative features. We can find that our model achieves best performance when we select around 10% of features.">

.. only:: html

  .. image:: /auto_examples/svm/images/thumb/sphx_glr_plot_svm_anova_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_svm_plot_svm_anova.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">SVM-Anova: SVM with univariate feature selection</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Plot the maximum margin separating hyperplane within a two-class separable dataset using a Support Vector Machine classifier with linear kernel.">

.. only:: html

  .. image:: /auto_examples/svm/images/thumb/sphx_glr_plot_separating_hyperplane_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_svm_plot_separating_hyperplane.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">SVM: Maximum margin separating hyperplane</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Find the optimal separating hyperplane using an SVC for classes that are unbalanced.">

.. only:: html

  .. image:: /auto_examples/svm/images/thumb/sphx_glr_plot_separating_hyperplane_unbalanced_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_svm_plot_separating_hyperplane_unbalanced.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">SVM: Separating hyperplane for unbalanced classes</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Plot decision function of a weighted dataset, where the size of points is proportional to its weight.">

.. only:: html

  .. image:: /auto_examples/svm/images/thumb/sphx_glr_plot_weighted_samples_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_svm_plot_weighted_samples.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">SVM: Weighted samples</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="The following example illustrates the effect of scaling the regularization parameter when using svm for svm_classification. For SVC classification, we are interested in a risk minimization for the equation:">

.. only:: html

  .. image:: /auto_examples/svm/images/thumb/sphx_glr_plot_svm_scale_c_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_svm_plot_svm_scale_c.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Scaling the regularization parameter for SVCs</div>
    </div>


.. raw:: html

    <div class="sphx-glr-thumbcontainer" tooltip="Toy example of 1D regression using linear, polynomial and RBF kernels.">

.. only:: html

  .. image:: /auto_examples/svm/images/thumb/sphx_glr_plot_svm_regression_thumb.png
    :alt:

  :ref:`sphx_glr_auto_examples_svm_plot_svm_regression.py`

.. raw:: html

      <div class="sphx-glr-thumbnail-title">Support Vector Regression (SVR) using linear and non-linear kernels</div>
    </div>


.. thumbnail-parent-div-close

.. raw:: html

    </div>


.. toctree::
   :hidden:

   /auto_examples/svm/plot_oneclass
   /auto_examples/svm/plot_svm_kernels
   /auto_examples/svm/plot_iris_svc
   /auto_examples/svm/plot_linearsvc_support_vectors
   /auto_examples/svm/plot_rbf_parameters
   /auto_examples/svm/plot_svm_margin
   /auto_examples/svm/plot_svm_tie_breaking
   /auto_examples/svm/plot_custom_kernel
   /auto_examples/svm/plot_svm_anova
   /auto_examples/svm/plot_separating_hyperplane
   /auto_examples/svm/plot_separating_hyperplane_unbalanced
   /auto_examples/svm/plot_weighted_samples
   /auto_examples/svm/plot_svm_scale_c
   /auto_examples/svm/plot_svm_regression

