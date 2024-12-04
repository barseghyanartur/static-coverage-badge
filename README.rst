=====================
Static coverage badge
=====================

.. image:: https://github.com/barseghyanartur/fake.py/actions/workflows/test.yml/badge.svg?branch=main
   :target: https://github.com/barseghyanartur/static-coverage-badge/actions
   :alt: Build Status

.. image:: https://img.shields.io/badge/license-MIT-blue.svg
   :target: https://github.com/barseghyanartur/static-coverage-badge/#License
   :alt: MIT

.. image:: https://github.com/barseghyanartur/static-coverage-badge/blob/coverage/coverage.svg?branch=main&service=github
    :target: https://barseghyanartur.github.io/static-coverage-badge/
    :alt: Coverage

.. References:

.. _coverage: https://coverage.readthedocs.io
.. _coverage-badge: https://github.com/dbrgn/coverage-badge
.. _actions-gh-pages: https://github.com/peaceiris/actions-gh-pages
.. _coveralls: https://coveralls.io

Generate coverage badge without third-party services, like `coveralls`_.

Why
===
Sometimes you can't use third-party services, but you do want to show
the coverage badge in your repository.

How
===
- Run the tests in GitHub Actions.
- After the tests, run the `coverage-badge`_ and store the `coverage.svg` in
  the current directory.
- Copy all files from `htmlcov` into current directory.
- Use `actions-gh-pages`_ to publish current directory to GitHub Pages.
- Update your static badges.

License
=======
MIT

Author
======
Artur Barseghyan
