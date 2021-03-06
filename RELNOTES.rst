======================
*Picire* Release Notes
======================

17.1
====

Summary of changes:

* Changed the working directory of each test subprocess from $CWD to the
  corresponding test directory.
* Added support for content-based result caching (in addition to the
  configuration-based approach).
* Minor bug fixes and improvements.


16.7
====

Summary of changes:

* Added py.test-based testing, and support for tox and Travis CI.
* API refactoring to allow better code reuse, especially by the *Picireny*
  project.
* Minor bug fixes and improvements.


16.5
====

First public release of the *Picire* Parallel Delta Debugging Framework.

Summary of main features:

* One sequential ("light") and two process-based parallel ("parallel" and
  "combined parallel") ddmin implementations.
* "Subset checks first" and "complement checks first" modes.
* "Forward", "backward", "random" (and "skip") iteration strategies for both
  subset and complement checks.
* "Zeller" and "balanced" split modes.
* Python 3 API and CLI.
