.. _`changelog`:

=========
Changelog
=========

``mlbscores`` issues are filed on `GitHub <https://github.com/kevinbowen777/mlbscores/issues>`_, and each ticket number here corresponds to a closed GitHub issue.

All notable changes to this project will be documented in this file.

The format is based on `Keep a Changelog <https://keepachangelog.com/en/1.0.0/>`_, and this project adheres to `Semantic Versioning <https://semver.org/spec/v2.0.0.html>`_.

This project uses `towncrier <https://towncrier.readthedocs.io/>`_ for keeping
the changelog. DO NOT commit any changes to this file.

Backward incompatible (breaking) changes should only be introduced in major versions
with advance notice in the **Deprecations** section of releases.


..
    You should *NOT* be adding new change log entries to this file, this
    file is managed by towncrier. You *may* edit previous change logs to
    fix problems like typo corrections or such.
    To add a new change log entry, please see
    https://pip.pypa.io/en/latest/development/contributing/#news-entries
    but note that in toolbox the "news/" directory is named "changelog/".

.. towncrier release notes start

mlbscores 0.1.0 (2026-06-24)
============================

Contributor-facing changes
--------------------------

-  (`#4 <https://github.com/kevinbowen777/mlbscores/issues/4>`_): Add towncrier CHANGELOG package.

-  (`#8 <https://github.com/kevinbowen777/mlbscores/issues/8>`_): Initialize as Poetry project.


Improved documentation
----------------------

- : Add CC0-1.0 license.

- : Add README.


New features
------------

- : Added player AVG to output of box score.

- : read/write 'bestteams' to configuration file.

-  (`#1 <https://github.com/kevinbowen777/mlbscores/issues/1>`_): Modify shebang to use non-system Python.

-  (`#3 <https://github.com/kevinbowen777/mlbscores/issues/3>`_): Improve descriptions of flags in --help.


Miscellaneous internal changes
------------------------------

-  (`#6 <https://github.com/kevinbowen777/mlbscores/issues/6>`_): Re-write datetime import.

mlbscores 0.0.2 (2019-03-03)
============================

Bug fixes
---------

- : Prevent null linescores from crashing.

- : Properly sort standings.


New features
------------

- : Implement timezones.

- : Migrate to Python 3.

- : Update to stats API.

mlbscores 0.0.1 (2016-05-01)
============================

New features
------------

- : Add standings.


Miscellaneous internal changes
------------------------------

- : Initial commit.
