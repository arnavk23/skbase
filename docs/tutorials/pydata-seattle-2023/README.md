PyData Seattle 2023 — sktime tutorial
=====================================

This folder is intended to host the material from the PyData Seattle 2023
`sktime` tutorial:

https://github.com/sktime/sktime-tutorial-pydata-seattle-2023

Work plan / migration notes
--------------------------

- The original tutorial lives in the external repository linked above. To
  permanently move the tutorial into this repository, copy the notebook and
  associated resource files into this `docs/tutorials/pydata-seattle-2023`
  directory.

- Add Binder configuration (``binder/``) and a minimal environment file
  (``environment.yml`` or ``requirements.txt``) so the tutorial can be run on
  Binder.

- Update docs navigation (the file ``docs/source/tutorials/pydata_seattle_2023.rst``)
  to include the tutorial pages or notebooks so they become part of the
  documentation site.

- Consider converting notebooks to Sphinx-friendly formats (``nbsphinx`` or
  ``myst-nb``) if you want rendered interactive notebooks in the docs site.

Proposed minimal checklist
--------------------------

1. Clone or copy the content from the original repository into this folder.
2. Add an ``environment.yml`` or ``requirements.txt`` capturing dependencies.
3. Add a ``binder/`` config if Binder is desired (``binder/requirements.txt`` or
   ``binder/postBuild`` as needed).
4. Add/convert notebooks into the docs via ``nbsphinx`` or ``myst-nb`` and
   update ``docs/source/tutorials/pydata_seattle_2023.rst`` to include them.
5. Run ``make docs`` (or the project's docs build command) and verify rendering.

License / attribution
---------------------

Preserve the original repository's license and attribution. When moving the
content, keep authorship notes and any LICENSE files attached to the
original tutorial.

Contact
-------

If you want, I can help copy the notebooks and add binder config. If you
approve, I will proceed to import the materials from the external repo and
convert them into Sphinx-ready pages.
