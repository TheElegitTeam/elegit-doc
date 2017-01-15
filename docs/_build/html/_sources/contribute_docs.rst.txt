.. _contribute-docs:

======================
Help Add Documentation
======================

Elegit is an educational tool. If there is something unclear that you would like to explain better, create documentation for it!

The documentation for Elegit is written in `reStructuredText <http://thomas-cokelaer.info/tutorials/sphinx/rest_syntax.html>`_ and generated using `Sphinx <http://www.sphinx-doc.org/en/1.5.1/>`_. You can add documentation files to our `documentation repository <https://github.com/TheElegitTeam/elegit-doc>`_. See below for more details on writing docs.

Installing Sphinx
----------------------
To parse the files written in reStructuredText into the actual HTML docs, we use a tool called Sphinx. To view your new pages or changes, you will first need to `install Sphinx <http://www.sphinx-doc.org/en/1.5.1/tutorial.html>`_ on your machine. The easiest way to install it is with ``pip install sphinx``.

Adding Files
------------
Existing and new pages should all be in the ``docs/`` directory. Before creating a new file, check to see if there is a relevant page that it would make more sense to add to. If you do create a new file, make sure you add it to the table of contents in ``index.rst`` or Sphinx will give you the warning::

    $ WARNING: document isn't included in any toctree

Simply open or create the ``.rst`` file you wish to edit and write away!

Creating HTML
-------------
Generating documentation from the ``.rst`` files is very easy. Simply run ``make html`` from the ``docs/`` directory and Sphinx will create the corresponding HTML. The results can be found in ``_build/html``.
