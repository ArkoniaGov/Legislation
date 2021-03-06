| Version:  
    ``0/0/0``
| Depends:  
    ``/leg/NationalSymbols.rst``
    ``/leg/TODO``
    ``http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html``
| References:

A.  Abstract
===========
#.  This file **denotes** the **specifications** which a prospective piece of **legislation must adhere to** in order for **to be legally added** to this repository.

B.  Contents
===========
#.  All legislation should be interpreted per this section's subsection(s).

    #.  Interpretation should proceed according to the current *de facto* primary language [5]_, as specified by ``/leg/NationalSymbols.rst``.
    
#.  All legislation must be written in compliance with this section's subsection(s).

    #.  Have filenames that comply with the specifications listed in this section's subsection(s).
    
        #.  Adequately describe the bill's contents.
        #.  Capitalize each word.
        #.  Have no spaces.
        #.  Have .rst at the end.
        #.  Have 30 or fewer characters [1]_, not counting '.rst'.
        
    #.  Have an internal structure that complies with the specifications listed in this section's subsection(s).
        
        #.  Each law must begin with metadata, and this metadata must consist only of certain data-points, these being defined by this section's subsection(s).
            
            #.  Version
            
                #.  (TODO)
                
            #.  Depends
            
                #.  (TODO)
                #.  Legislation is not considered to depend upon this law simply because it is compliant with the specifications of this law.
                
            #.  References
            
                #.  (TODO)
                
        #.  Post-metadata, each law may only contain sections that match the requirements of this section's subsection(s).
        
            #.  The first section should be entitled 'Abstract', and should be compliant with this section's subsection(s).
            
                #.  This section should summarize what the law does.  
                #.  This section may mention the law's purpose, and previous work in the area.  
                #.  This section may not be longer than 400 words [1]_.
                #.  This section is not legally binding.

            #.  The second section should be entitled 'Contents', and should be compliant with this section's subsection(s).
                
                #.  This section contains the legislation itself.
                #.  This section is legally binding.
                
            #.  The third section should be entitled 'Footnotes', and should be compliant with this section's subsection(s).
            
                #.  This section contains the contents of the various footnotes referenced throughout a law.  
                #.  This section may be left out if the law has no footnotes.  
                #.  This section is not legally binding.
                
        #.  The contents of each law must additionally meet the formatting-requirements specified in this section's subsections.
        
            #.  Laws must be fully compatible with the reStructuredText format, as specified at ``http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html``.
            #.  It is encouraged to embolden the most important parts of a law [2]_ [4]_, although emboldening within footnotes is unnecessary, except where otherwise stated.  
            #.  Outside of the 'Footnotes' section itself, footnotes do not need to appear in order -- although drafters are encouraged to place them so, especially in shorter laws.
                    
            #.  Metadata must be formatted in a specific way, as defined by this section's subsection(s).
            
                #.  (TODO)
                
#.  Legislation may only depend upon files in ``/leg`` and ``/res``
#.  Files in ``/res`` may not depend upon anything [3]_.
#.  Variables intended for ``/var`` must be placed into a subdirectory of ``/var``, and that subdirectory must have a name equivalent to the name of the academic discipline of the jury which has the right to modify that variable [6]_.  This provision is dependent upon ``/leg/TODO``.
#.  Variables must be prefixed with a shorthand for their type, as specified by this section's subsection(s).

C.  Footnotes
===========
.. [1]  This number is arbitrary.
.. [2]  This is intended to make legislation easier to speed-read.
.. [3]  This is because files in ``/res`` are intended to allow nomocracy to expand beyond mere text, but are not intended to provide a workaround for standard legislative procedure.
.. [4]  A suggested way to go about this, is to embolden such that, when only the emboldened text is read, the gist of the law can be gained, even if the emboldened text is, by itself, not entirely grammatical.
.. [5]  As a quick fyi, this means that all numbers are base-twelve.
.. [6]  This is intended to reduce clutter within directories.
