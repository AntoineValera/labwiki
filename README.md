# labwiki
 
Source code to build SilverLab Wiki hosted on ReadTheDocs.

See Wiki on: https://silverlab-wiki.readthedocs.io/


### Contributors

To edit the documention content, edit or add .rst files ([ReStructured Text](https://thomas-cokelaer.info/tutorials/sphinx/rest_syntax.html)) to the source directory [labwiki/source](/source). 

Remember to include new files in [toctrees](https://www.sphinx-doc.org/en/1.5/markup/toctree.html) to manage site navigation. You can add to [master toctree](/source/index.rst) (also adds to List of Contents on Home Page) or to toctrees for [individual sections] (/source/data/dataindex.rst).

HTML pages are automatically generated via Sphinx, with automatic build managed by ReadTheDocs service. 
