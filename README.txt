Introduction
============

This package contains Go Mobile mobile add-on product for Plone documentation in Sphinx format.
Necessary scripts to generate HTML documentation and upload it to a Plone site are supplied.

Compiling the documentation
----------------------------

Example::

        source ~/py24/bin/activate # Enter virtualenv
        
        python bootstrap.py 
        
        bin/buildout # will return error
        
        bin/develop co ""
        
        bin/buildout
        
        bin/sphinx-build manual build
        

Author
------

`mFabrik Research Oy <mailto:info@mfabrik.com>`_ - Python and Plone professionals for hire.

* `mFabrik web site <http://mfabrik.com>`_ 

* `mFabrik mobile site <http://mfabrik.mobi>`_ 

* `Blog <http://blog.mfabrik.com>`_

* `More about Plone <http://mfabrik.com/technology/technologies/content-management-cms/plone>`_ 

       
       


