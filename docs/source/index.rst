Welcome to pylegendmeta's documentation!
========================================

*pylegendmeta* is a Python package to access arbitrary text file databases,
based on :mod:`dbetto` but specialized to the legend-metadata_ repository,
which stores `LEGEND metadata
<https://legend-exp.github.io/legend-data-format-specs/dev/metadata>`_.

Getting started
---------------

*pylegendmeta* is published on the `Python Package Index
<https://pypi.org/project/pylegendmeta>`_. Install on local systems with `pip
<https://pip.pypa.io/en/stable/getting-started>`_:

.. tab:: Stable release

    .. code-block:: console

        $ pip install pylegendmeta

.. tab:: Unstable (``main`` branch)

    .. code-block:: console

        $ pip install pylegendmeta@git+https://github.com/legend-exp/pylegendmeta@main#egg=legendmeta

Next steps
----------

.. toctree::
   :maxdepth: 1

   tutorial
   kitchen-sink
   Package API reference <api/modules>

.. _legend-metadata: https://github.com/legend-exp/legend-metadata
