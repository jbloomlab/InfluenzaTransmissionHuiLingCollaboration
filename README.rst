========================================================
Influenza transmission with Hui-Ling Yen
========================================================
This repository describes computational work associated with a study led by `Hui-Ling Yen`_ to examine influenza transmission in ferrets. The computational work is performed by `Jesse Bloom`_.

The work is performed in a set of `iPython notebook`_\s. The `Notebooks`_ listed below describe each analysis. The `Input data files`_ are also detailed below.

Notebooks
------------
Each of the following is an `iPython notebook`_ describing a particular analysis:

* `SequenceAnalysisAndSynonymousBarcoding.ipynb <SequenceAnalysisAndSynonymousBarcoding.ipynb>`_ describes an analysis of the *A/California/04/2009* pdmH1N1 sequences in `Hui-Ling Yen`_\'s reverse-genetics plasmids, and the design of synonymously barcoded variants.


Input data files
------------------

* The ``./sequences/`` subdirectory contains sequences.

    - ``all_pdmH1N1_seqs.fasta`` contains all full-length human H1N1 sequences annotated as *pandemic H1N1* as downloaded from the `Influenza Virus Resource`_ on September-5-2015.

    - ``plasmid_sequences_20150904.txt`` gives the sequences of the reverse genetics plasmids are provided by `Hui-Ling Yen`_ on September-4-2015.


.. _`Influenza Virus Resource`: http://www.ncbi.nlm.nih.gov/genomes/FLU/FLU.html
.. _`Hui-Ling Yen`: http://sph.hku.hk/en/about-us/faculty-and-staff/academic-staff/yen,-hui-ling
.. _`Jesse Bloom`: http://research.fhcrc.org/bloom/en.html
.. _`iPython notebook`: http://ipython.org/notebook.html
