:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'quantms-utils'
.. highlight: bash

quantms-utils
=============

.. conda:recipe:: quantms-utils
   :replaces_section_title:
   :noindex:

   Python package with scripts and helpers for the quantms workflow

   :homepage: https://www.github.com/bigbio/quantms-utils
   :license: MIT
   :recipe: /`quantms-utils <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/quantms-utils>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/quantms-utils/meta.yaml>`_

   


.. conda:package:: quantms-utils

   |downloads_quantms-utils| |docker_quantms-utils|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>0.0.11-0</code>,  <code>0.0.10-0</code>,  <code>0.0.9-0</code>,  <code>0.0.8-0</code>,  <code>0.0.7-0</code>,  <code>0.0.6-0</code>,  <code>0.0.5-0</code>,  <code>0.0.4-0</code>,  <code>0.0.3-0</code>,  </span></summary>
      

      ``0.0.11-0``,  ``0.0.10-0``,  ``0.0.9-0``,  ``0.0.8-0``,  ``0.0.7-0``,  ``0.0.6-0``,  ``0.0.5-0``,  ``0.0.4-0``,  ``0.0.3-0``,  ``0.0.2-0``

      
      .. raw:: html

         </details>
      

   
   :depends click: ``>=7.0``
   :depends deeplc: ``2.2.38``
   :depends deeplcretrainer: 
   :depends ms2pip: ``4.0.0.dev8``
   :depends ms2rescore: ``3.0.3``
   :depends numpy: 
   :depends pandas: ``>=1.0.0``
   :depends psm-utils: ``0.8.2``
   :depends pydantic: ``>=1.10,<2``
   :depends pyopenms: ``>=2.9.1``
   :depends python: ``>=3.7.0,<4.0.0``
   :depends scikit-learn: 
   :depends scipy: ``1.13.1``
   :depends sdrf-pipelines: ``>=0.0.29``
   :requirements:

   .. rubric:: Installation

  You need a conda-compatible package manager
  (currently either `micromamba <https://mamba.readthedocs.io>`_, `mamba <https://mamba.readthedocs.io>`_, or `conda <https://docs.conda.io/projects/conda>`_)
  and the Bioconda channel already activated (see :ref:`set-up-channels`).

  While any of above package managers is fine, it is currently recommended to use either
  micromamba or mamba (see `here <https://mamba.readthedocs.io>`_ for installation instructions).
  We will show all commands using mamba below, but the arguments are the same for the two
  others.

  Given that you already have a conda environment in which you want to have this package, install with::

      mamba install quantms-utils

   and update with::

      mamba update quantms-utils

  To create a new environment, run::

      mamba create --name myenvname quantms-utils

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/quantms-utils:<tag>

   (see `quantms-utils/tags`_ for valid values for ``<tag>``)


.. |downloads_quantms-utils| image:: https://img.shields.io/conda/dn/bioconda/quantms-utils.svg?style=flat
   :target: https://anaconda.org/bioconda/quantms-utils
   :alt:   (downloads)
.. |docker_quantms-utils| image:: https://quay.io/repository/biocontainers/quantms-utils/status
   :target: https://quay.io/repository/biocontainers/quantms-utils
.. _`quantms-utils/tags`: https://quay.io/repository/biocontainers/quantms-utils?tab=tags


.. raw:: html

    <script>
        var package = "quantms-utils";
        var versions = ["0.0.11","0.0.10","0.0.9","0.0.8","0.0.7"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/quantms-utils/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/quantms-utils/README.html