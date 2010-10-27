Introduction
============

This package contains Go Mobile mobile add-on product for Plone documentation in Sphinx format.
Necessary scripts to generate HTML documentation and upload it to a Plone site are supplied.

Compiling the documentation
----------------------------

Example::

        source ~/python2.6/bin/activate # Enter virtualenv
        
        python bootstrap.py 
        
        bin/buildout # will return error
        
        bin/develop co ""
        
        bin/buildout
                
        rm -rf build/* ; bin/sphinx-build manual build
        
Uploading the documentation
-----------------------------

Create Plone Help Center content type *Reference manual* with id *documentation* on your site.

Then upload the documentation using Zope's XML-RPC machinery using the following script command::         
        
        bin/toplone http://admin:x@webandmobile.mfabrik.com/docs/web-and-mobile

Author
------

`mFabrik Research Oy <mailto:info@mfabrik.com>`_ - Python and Plone professionals for hire.

* `mFabrik web site <http://mfabrik.com>`_ 

* `mFabrik mobile site <http://mfabrik.mobi>`_ 

* `Blog <http://blog.mfabrik.com>`_

* `More about Plone <http://mfabrik.com/technology/technologies/content-management-cms/plone>`_ 

       
       


