:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-gatom'
.. highlight: bash

bioconductor-gatom
==================

.. conda:recipe:: bioconductor-gatom
   :replaces_section_title:
   :noindex:

   Finding an Active Metabolic Module in Atom Transition Network

   :homepage: https://bioconductor.org/packages/3.18/bioc/html/gatom.html
   :license: MIT + file LICENCE
   :recipe: /`bioconductor-gatom <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gatom>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gatom/meta.yaml>`_

   This package implements a metabolic network analysis pipeline to identify an active metabolic module based on high throughput data. The pipeline takes as input transcriptional and\/or metabolic data and finds a metabolic subnetwork \(module\) most regulated between the two conditions of interest. The package further provides functions for module post\-processing\, annotation and visualization.


.. conda:package:: bioconductor-gatom

   |downloads_bioconductor-gatom| |docker_bioconductor-gatom|

   :versions:
      
      

      

      

   
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

      mamba install bioconductor-gatom

   and update with::

      mamba update bioconductor-gatom

  To create a new environment, run::

      mamba create --name myenvname bioconductor-gatom

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/bioconductor-gatom:<tag>

   (see `bioconductor-gatom/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-gatom| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-gatom.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-gatom
   :alt:   (downloads)
.. |docker_bioconductor-gatom| image:: https://quay.io/repository/biocontainers/bioconductor-gatom/status
   :target: https://quay.io/repository/biocontainers/bioconductor-gatom
.. _`bioconductor-gatom/tags`: https://quay.io/repository/biocontainers/bioconductor-gatom?tab=tags


.. raw:: html

    <script>
        var package = "bioconductor-gatom";
        var versions = [];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-gatom/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-gatom/README.html