sphinx based api documentation

install sphinx and sphinx_rtd_theme

    $ conda install sphinx sphinx_rtd_theme

rst files generation::

    $ sphinx-apidoc /Library/Python/2.7/site-packages/OCC --separate -o api_doc

Then::

    $ make html
