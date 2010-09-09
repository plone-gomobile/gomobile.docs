Build and upload instructions
------------------------------

Install PloneHelpCenter 4.0+. 

Enable HelpCenterManual as implicitly in portal_types.

Make Sphinx HTML::

        make clean html
        
Upload::

        bin/toplone http://x:y@localhost:8080/webandmobile/for-developers/go-mobile-for-plone-documentation 
                