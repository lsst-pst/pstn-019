.. image:: https://img.shields.io/badge/pstn--019-lsst.io-brightgreen.svg
   :target: https://pstn-019.lsst.io
.. image:: https://travis-ci.com/lsst-pst/pstn-019.svg
   :target: https://travis-ci.com/lsst-pst/pstn-019

####################################################
The Vera C. Rubin Observatory LSST Science Pipelines
####################################################

PSTN-019
========



Links
=====

- Live drafts: https://pstn-019.lsst.io
- GitHub: https://github.com/lsst-pst/pstn-019

Build
=====

This repository includes lsst-texmf_ as a Git submodule.
Clone this repository::

    git clone --recurse-submodules https://github.com/lsst-pst/pstn-019

Compile the PDF::

    make

Clean built files::

    make clean

Updating lsst-texmf
-------------------

`lsst-texmf`_ includes BibTeX files, the ``lsstdoc`` class file, and acronym definitions, among other essential tooling for LSST's LaTeX documentation projects.
To update to a newer version of `lsst-texmf`_, you can update the submodule in this repository::

   git submodule update --init --recursive

Commit, then push, the updated submodule.

.. _lsst-texmf: https://github.com/lsst/lsst-texmf
