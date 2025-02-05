sphinx-codeautolink
===================
|pypi| |license| |readthedocs| |build|

Automatic links from Python code examples to reference documentation
at the flick of a switch!
sphinx-codeautolink analyses the code in your documentation
and inserts links to definitions that you use.

For a live demo, see our online documentation on
`Read The Docs <https://sphinx-codeautolink.rtfd.org>`_.

sphinx-codeautolink elsewhere:

- Package on `PyPI <https://pypi.org/project/sphinx-codeautolink>`_
- How to contribute on `GitHub <https://github.com/felix-hilden/
  sphinx-codeautolink/blob/master/contributing.rst>`_

Installation
------------

.. code:: sh

   $ pip install sphinx-codeautolink

To enable sphinx-codeautolink, modify the extension list in ``conf.py``.
Note that the extension name uses an underscore rather than a hyphen.

.. code:: python

   extensions = [
       ...,
       "sphinx_codeautolink",
   ]

That's it! Now your code examples are linked.
For ways of concatenating multiple examples
and setting default import statements among other things,
have a look at the online documentation.

.. |pypi| image:: https://img.shields.io/pypi/v/sphinx-codeautolink.svg
   :target: https://pypi.org/project/sphinx-codeautolink
   :alt: PyPI package

.. |license| image:: https://img.shields.io/badge/License-MIT-blue.svg
   :target: https://choosealicense.com/licenses/mit
   :alt: License: MIT

.. |readthedocs| image:: https://rtfd.org/projects/sphinx-codeautolink/badge/?version=latest
   :target: https://sphinx-codeautolink.rtfd.org/en/latest/
   :alt: documentation

.. |build| image:: https://github.com/felix-hilden/sphinx-codeautolink/workflows/CI/badge.svg
   :target: https://github.com/felix-hilden/sphinx-codeautolink/actions
   :alt: build status
