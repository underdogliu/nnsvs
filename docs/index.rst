.. nnsvs documentation master file, created by
   sphinx-quickstart on Fri Apr 24 00:51:13 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

NNSVS
=====

Neural network based singing voice synthesis library

https://github.com/nnsvs/nnsvs

Features
--------

- **Open-source**: NNSVS is fully open-source. You can create your own voicebanks with your dataset.
- **Multiple languages**: NNSVS has been used for creating singing voice synthesis (SVS) systems for multiple languages by VocalSynth comminities (8+ as far as I know).
- **Research friendly**: NNSVS comes with reproducible Kaldi/ESPnet-style recipes. You can use NNSVS to create baseline systems for your research.

Note that NNSVS was originally designed for research purposes. Please check out more user-friendly `ENUNU <https://github.com/oatsu-gh/ENUNU>`_ for creative purposes.
You can find a practical guide for NNSVS/ENUNU at https://nnsvs.carrd.co/ (by `xuu <https://xuu.crd.co/>`_).
A detailed tutorial for for making voice banks can be found at `NNSVS Database Making Tutorial <https://docs.google.com/document/d/1uMsepxbdUW65PfIWL1pt2OM6ZKa5ybTTJOpZ733Ht6s/edit?usp=sharing>`_ (by `PixProcuer <https://twitter.com/PixPrucer>`_).

Audio samples
-------------

Samples by r9y9: https://soundcloud.com/r9y9/sets/dnn-based-singing-voice

Online demo
-----------

https://share.streamlit.io/r9y9/nnsvs/streamlit_demo/app.py

Selected videos
---------------

Demo by https://github.com/DYVAUX


..  youtube:: 0sSd31TUVCU
   :align: center

You can find more from the NNSVS/ENUNU community: `YouTube <https://www.youtube.com/results?search_query=nnsvs+enunu>`_, `NicoNico <https://www.nicovideo.jp/search/nnsvs?ref=nicotop_search>`_


.. toctree::
   :maxdepth: 1
   :caption: Demos

   notebooks/Demos
   notebooks/NNSVS_vs_Sinsy

.. toctree::
   :maxdepth: 1
   :caption: Guides

   installation
   recipes
   custom_models
   devdocs
   update_guide

.. toctree::
   :maxdepth: 1
   :caption: Advanced guides

   optuna
   train_postfilters
   train_vocoders


.. toctree::
   :maxdepth: 1
   :caption: Notes

   overview
   tips

.. toctree::
   :maxdepth: 1
   :caption: Package reference

   modules/base
   modules/model
   modules/acoustic_models
   modules/postfilters
   modules/discriminators
   modules/pretrained
   modules/svs
   modules/dsp
   modules/gen
   modules/mdn
   modules/pitch
   modules/multistream
   modules/util
   modules/train_util

.. toctree::
   :maxdepth: 1
   :caption: Resources

   links
   papers

.. toctree::
    :maxdepth: 1
    :caption: Meta information

    changelog


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
