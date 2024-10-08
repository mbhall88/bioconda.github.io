:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'cobs'
.. highlight: bash

cobs
====

.. conda:recipe:: cobs
   :replaces_section_title:
   :noindex:

   Compact Bit\-Sliced Signature Index \(for Genomic k\-Mer Data or q\-Grams\)

   :homepage: https://panthema.net/cobs
   :license: MIT
   :recipe: /`cobs <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/cobs>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/cobs/meta.yaml>`_

   


.. conda:package:: cobs

   |downloads_cobs| |docker_cobs|

   :versions:
      
      

      ``0.3.0-1``,  ``0.3.0-0``,  ``0.2.1-2``,  ``0.2.1-1``,  ``0.2.1-0``,  ``0.2.0-0``,  ``0.1.2-2``,  ``0.1.2-1``,  ``0.1.2-0``

      

   
   :depends _openmp_mutex: ``>=4.5``
   :depends boost-cpp: ``>=1.72.0,<1.72.1.0a0``
   :depends libgcc-ng: ``>=12``
   :depends libstdcxx-ng: ``>=12``
   :depends libzlib: ``>=1.2.13,<1.3.0a0``
   :depends zlib: 
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

      mamba install cobs

   and update with::

      mamba update cobs

  To create a new environment, run::

      mamba create --name myenvname cobs

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/cobs:<tag>

   (see `cobs/tags`_ for valid values for ``<tag>``)


.. |downloads_cobs| image:: https://img.shields.io/conda/dn/bioconda/cobs.svg?style=flat
   :target: https://anaconda.org/bioconda/cobs
   :alt:   (downloads)
.. |docker_cobs| image:: https://quay.io/repository/biocontainers/cobs/status
   :target: https://quay.io/repository/biocontainers/cobs
.. _`cobs/tags`: https://quay.io/repository/biocontainers/cobs?tab=tags


.. raw:: html

    <script>
        var package = "cobs";
        var versions = ["0.3.0","0.3.0","0.2.1","0.2.1","0.2.1"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/cobs/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/cobs/README.html