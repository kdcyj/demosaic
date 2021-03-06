Colour - Demosaicing
====================

A `Python <https://www.python.org/>`__ package implementing various
CFA (Colour Filter Array) demosaicing algorithms and related utilities.

It is open source and freely available under the
`New BSD License <https://opensource.org/licenses/BSD-3-Clause>`__ terms.

..  image:: https://raw.githubusercontent.com/colour-science/colour-demosaicing/master/docs/_static/Demosaicing_001.png

.. contents:: **Table of Contents**
    :backlinks: none
    :depth: 3

.. sectnum::

Features
--------

The following CFA (Colour Filter Array) demosaicing algorithms are implemented:

-   Bilinear
-   Malvar (2004)
-   DDFAPD - Menon (2007)

Installation
------------

Because of their size, the resources dependencies needed to run the various
examples and unit tests are not provided within the Pypi package. They are
separately available as
`Git Submodules <https://git-scm.com/book/en/v2/Git-Tools-Submodules>`__
when cloning the
`repository <https://github.com/colour-science/colour-demosaicing>`__.

Primary Dependencies
^^^^^^^^^^^^^^^^^^^^

**Colour - Demosaicing** requires various dependencies in order to run:

-  `Python 2.7 <https://www.python.org/download/releases/>`__ or
   `Python 3.7 <https://www.python.org/download/releases/>`__
-  `Colour Science <https://www.colour-science.org>`__

Pypi
^^^^

Once the dependencies satisfied, **Colour - Demosaicing** can be installed from
the `Python Package Index <http://pypi.python.org/pypi/colour-demosaicing>`__ by
issuing this command in a shell::

	pip install colour-demosaicing

The tests suite dependencies are installed as follows::

    pip install 'colour-demosaicing[tests]'

The documentation building dependencies are installed as follows::

    pip install 'colour-demosaicing[docs]'

The overall development dependencies are installed as follows::

    pip install 'colour-demosaicing[development]'

Usage
-----

API
^^^

The main reference for
`Colour - Demosaicing <https://github.com/colour-science/colour-demosaicing>`__
is the manual:

.. toctree::
    :maxdepth: 4

    manual

Examples
^^^^^^^^

Various usage examples are available from the
`examples directory <https://github.com/colour-science/colour-demosaicing/tree/master/colour_demosaicing/examples>`__.

Contributing
------------

If you would like to contribute to `Colour - Demosaicing <https://github.com/colour-science/colour-demosaicing>`__,
please refer to the following `Contributing <https://www.colour-science.org/contributing/>`__
guide for `Colour <https://github.com/colour-science/colour>`__.

Bibliography
------------

The bibliography is available in the repository in
`BibTeX <https://github.com/colour-science/colour-demosaicing/blob/develop/BIBLIOGRAPHY.bib>`__
format.

Code of Conduct
---------------

The *Code of Conduct*, adapted from the `Contributor Covenant 1.4 <https://www.contributor-covenant.org/version/1/4/code-of-conduct.html>`__,
is available on the `Code of Conduct <https://www.colour-science.org/code-of-conduct/>`__ page.

About
-----

| **Colour - Demosaicing** by Colour Developers
| Copyright © 2015-2019 – Colour Developers – `colour-science@googlegroups.com <colour-science@googlegroups.com>`__
| This software is released under terms of New BSD License: https://opensource.org/licenses/BSD-3-Clause
| `https://github.com/colour-science/colour-demosaicing <https://github.com/colour-science/colour-demosaicing>`__
