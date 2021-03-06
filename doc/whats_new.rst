.. _whats_new:

.. currentmodule:: pystan

============
 What's New 
============

v.2.0.1.0 (24. October 2013)
============================

- Updated to Stan 2.0.1.
- Specifying ``sample_file`` now works as expected.

v.2.0.0.1 (23. October 2013)
============================

- Stan ``array`` parameters are now handled correctly.
- Ancillary methods added to fit instances.
- Fixed bug that caused parameters in ``control`` dict to be ignored.

v.2.0.0.0 (21. October 2013)
============================

- Stan source updated to to 2.0.0.
- PyStan version now mirrors Stan version.
- Rudimentary plot and traceplot methods have been added to fit instances.
- Warmup and sampling progress now visible.

v.0.2.2 (28. September 2013)
============================

- ``log_prob`` method available from StanFit instances.
- Estimated sample size and Rhat included in summary.

v.0.2.1 (17. September 2013)
============================

- ``StanModel`` instances can now be pickled.
- Adds basic support for saving output to ``sample_file``.

v.0.2.0 (25. August 2013)
=========================

- ``optimizing`` method working for scalar, vector, and matrix parameters
- stanfit objects now have ``summary`` and ``__str__`` methods à la RStan
- stan source updated to commit cc82d51d492d26f754fd56efe22a99191c80217b (July 26, 2013)
- IPython-relevant bug fixes

v.0.1.1 (19. July 2013)
=======================

- Support for Python 2.7 and Python 3.3
- ``stan`` and ``stanc`` working with common arguments
