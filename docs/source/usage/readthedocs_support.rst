ReadTheDocs
===========

#.  Import Project 
#.  Add readthedoc.yaml file
#.  Add folders
    * :file:`/docs/build`  for sphinx files
    * :file:`/src`  for code
#.  Set-up sphinxs

    .. code-block:: python
        :linenos:

        cd docs
        sphinx-quickstart

#.  Add :file:`/docs/build` to :file:`.gitignore`. There is no need to always commit the updated html files as long as the '*'.rst-files 
    in the source folder are commited
#.  Make local changes and build html files with

    .. code-block:: python
        :linenos:

        ./make.bat html

    and check apprearance of webpage by right clicking html files in /docs/build/html. 
    Here we can also debug the rst files. - Check error messages.
#.  Commit from time to time to master branch. Only master branch is used to build 
    the webpage with ReadTheDocs.
#.  On the ReadTheDocs Account on the Webbrowser press "Build". When Error appear 
    it usually can be resolved from the :file:`conf.py` file

:kbd:`ctrl` + :kbd:`s`

.. image:: ../_static/test.png
    :width: 300px
    :target: https://typo3.org
    :alt: alt text

    
    
    