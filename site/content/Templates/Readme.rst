Some Nice "Readme":

- https://github.com/tmrts/boilr

Code (deprecated -- Use a boilr template)

..code::  

    Project Outline
    ----------------

    Project Goals
    '''''''''''''
    
    1. This is a project goal

    This project is intended to cover the gap found during {foo}

    Similar Work
    ''''''''''''

    Justification
    '''''''''''''

    Limitations
    '''''''''''
    
    Note: This list also constitutes a "Todo"
    
    - Alerting policies not yet implemented.

    Alerting Policies
    '''''''''''''''''

    ======================= ===============================================
    Policy                  Description
    ----------------------- -----------------------------------------------
    GET / (https) not 200   Check whether the HTTPS homepage is working
    GET / (http) not 302    Check whether the site is redirecting from HTTP
    ======================= ===============================================

    Security Alerts
    '''''''''''''''

    CVRFv1.1 ATOM Feed: https://feeds.littleman.co/security/{project}.atom _[FIG9]
    JSON: https://feeds.littleman.co/security/{project}.json _[FIG9]

    Summary
    '''''''
    
    ============= ============ ==============
    License       Code Style   Locale
    ------------- ------------ --------------
    Apache-2      Zend         en-AU [lang]_
    ============= ============ ==============

    Compatibility
    '''''''''''''

    Magento  Compatibility
    
    ===== ===== ===== ===== ===== =====
     1.9   1.8   1.7   1.6   1.5   1.4 
    ----- ----- ----- ----- ----- -----
      Y     ?     ?     ?     ?     ?
    ===== ===== ===== ===== ===== =====

    Installation 
    -------------
    Add the satis repository
        .. code::
        {
           "repositories": [
               {
                   "type": "composer",
                   "url": "http://satis.howden.io"
               }
           ]
        }

    Do a thing

    Usage
    -----
    
    Example A
    '''''''''
    
    This is an example.
    .. code::
        // This is an example code
        <?php echo $foo; ?>

    Thanks
    ------
    
    - Company A (https://www.littleman.co/)
    - Software B (https://software.com/)
    - Person C (https://personalwebsite.com) @twitterHandle

    Contributing
    ------------
    
    Contributions are always welcome! Nothing is too small, and the best place to start is to open an issue.

    References
    -----------
    
    .. [lang] Lingoes.net,. (2015). Language Code Table. Retrieved 4 June 2015, from http://www.lingoes.net/en/translator/langcode.htm
    .. [FIG9] GitHub, (2015). Proposed: security disclosure publication. Retrieved 15 May 2016, from https://github.com/php-fig/fig-standards/blob/master/proposed/security-disclosure-publication.md

Conclude readme template
