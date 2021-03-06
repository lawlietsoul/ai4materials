.. ai4materials documentation master file, created by
   sphinx-quickstart on Mon Mar 26 14:24:50 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to ai4materials's documentation!
=========================================

ai4materials allows to perform complex analysis of materials science data, using machine learning and compressed sensing techniques. It also
provide functions to pre-process (on parallel processors), save and subsequently load materials science datasets,
thus easing the traceability, reproducibility, and prototyping of new models.

On the left panel, you can find a few examples that showcase what ai4materials can do.

Finally, with ai4materials you can reproduce results from the following publications:

.. [1] A. Ziletti, A. Leitherer, M. Scheffler, and L. M. Ghiringhelli,
   "Crystal-structure classification via Bayesian deep learning: towards superhuman performance", in preparation (2018)

.. [2] A. Ziletti, D. Kumar, M. Scheffler, and L. M. Ghiringhelli, "Insightful classification of crystal structures
   using deep learning," Nature Communications, vol. 9, pp. 2775, 2018.
   [`Link to article <https://www.nature.com/articles/s41467-018-05169-6>`_]

.. [3] L. M. Ghiringhelli, J. Vybiral, S. V. Levchenko, C. Draxl, and M. Scheffler, “Big Data of Materials
   Science: Critical Role of the Descriptor,” Physical Review Letters, vol. 114, no. 10, p. 105503 .
   [`Link to article <https://link.aps.org/doi/10.1103/PhysRevLett.114.105503>`_]

.. codeauthor:: Angelo Ziletti <angelo.ziletti@gmail.com>


.. toctree::
   :maxdepth: 4
   :glob:
   :caption: Contents:

   installation  
   ai4materials.dataprocessing          
   ai4materials.descriptors          
   ai4materials.wrappers        
   ai4materials.models          
   ai4materials.interpretation    
   ai4materials.visualization        
   ai4materials.utils          
   authors
   history
   #contributing

Module contents
---------------


.. automodule:: ai4materials
    :members:
    :undoc-members:
    :show-inheritance:


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
