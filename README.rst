Pillow Python 3
===============

Proposal submitted to the Python Software Foundation February 28, 2013.

Grant Proposal
--------------

Provide funding to facilitate a Python 3 compatible release of the Python Imaging Library (via the Pillow fork).

Abstract
~~~~~~~~

The Python Imaging Library is one of the oldest and most popular third party libraries available to Python programmers today. It adds support for opening, manipulating, and saving many different image file formats. [1]_

Pillow is a popular and well-maintained packaging fork of the Python Imaging Library. At the time of this writing it has been downloaded over a quarter million times from the Python Package Index. [2]_

Python 3 is the next generation Python interpreter, whose adoption rate is gradually increasing. [3]_ A Python 3 compatible release of the Python Imaging Library will help increase the adoption rate of Python 3.

History
~~~~~~~

Tired of seeing the proliferation of third party packagings of the Python Imaging Library, in 2010 Alex Clark took Hanno Schlicting's repackaging [4]_ and used it to create a fork of the Python Imaging Library on GitHub. He subsequently released that fork to PyPI as Pillow 1.0 [5]_.

The ability to add additional development library paths to ``setup.py`` (e.g. 64 bit library and headers directories) and make releases quickly eventually led to widespread adoption of Pillow.

A little over a year later on 2011-09-08, Takayuki Shimizukawa [6]_ uploaded the first Windows (win32) eggs. Since then, every Pillow release included Windows eggs thanks to Takayuki. And on 2013-02-02, the first 64-bit Windows eggs (amd64) were uploaded to PyPI by Takayuki.

For the first 3 years, the fork focused on packaging fixes only. Now a Python 3 compatible pull request from Brian Crowell [7]_ has been merged, and the final stages of release preparation are underway.

In early 2013, Barry Warsaw created an Ubuntu Personal Package Archive and tested it with Python 3 [8]_. And the Fedora Project is now planning to include Pillow with their release of Fedora 19.

Finally, the Pillow project has promised a Python 3 compatible release of Pillow by PyCon 2013. Unfortunately as a volunteer, Alex Clark has been unable to allocate the time needed to properly complete the remaining critical tasks. Funding from the Python Software Foundation would help make it possible for him to do so [10]_.

Grant objective
---------------

To provide a Python 3 compatible release of the Python Imaging Library via the Pillow fork. The following tasks remain:

- Review and merge 10 outstanding pull requests: https://github.com/python-imaging/Pillow/pulls
    - https://github.com/python-imaging/Pillow/pull/64 ( Testing improvements and better Python 3.x support )
    - https://github.com/python-imaging/Pillow/pull/60 ( Py3k libraries path fix (issue #41) )
    - https://github.com/python-imaging/Pillow/pull/59 ( Fix issue #52 )
    - https://github.com/python-imaging/Pillow/pull/57 ( Updated tags to the 2.3 standard and fixed spelling error in the comment... )
    - https://github.com/python-imaging/Pillow/pull/56 ( BUG: PIL Image array interface has the wrong size for YCbCr )
    - https://github.com/python-imaging/Pillow/pull/55 ( Fix pildriver script )
    - https://github.com/python-imaging/Pillow/pull/54 ( Fix Windows 64 bit issues )
    - https://github.com/python-imaging/Pillow/pull/53 ( BUG: Windows image viewer unable to open image )
    - https://github.com/python-imaging/Pillow/pull/45 ( Fix rendered characters have been chipped for some TrueType fonts )
    - https://github.com/python-imaging/Pillow/pull/40 ( I wirte some simple demos, please merge it )
- Test the release on 3 major operating systems: Windows (e.g. XP, Server 2008), Linux (e.g. Ubuntu 12.04 LTS), Mac OS X.
- Test the release on 3 major Python releases: 2.6, 2.7, 3.3.
- Release Pillow 2.0 source distribution to the Python Package Index.

Grant size
----------

$1,300 USD total [11]_:

- $1,200 USD to pay for 24 hours of Alex Clark's development time @ $50/hour.
- $100 USD to pay for 2 hours of David Schmidt's development time @ $50/hour.

Grant beneficiaries
-------------------

ACLARK.NET, LLC is a team of professionals specializing in Python-based web applications & open source software and communities. Alex Clark is a self-employed Python Web Developer at ACLARK.NET, LLC. He is also the Pillow fork author and maintainer, and has contributed over 100 hours to Pillow development and maintenance.

David Schmidt is a student in Germany and has contributed over 30 hours of development time to Pillow.

Preferred method of funds delivery
----------------------------------

A check made payable to::

    ACLARK.NET, LLC

And sent to::

    ACLARK.NET, LLC
    XXXX XXXXXXXX XX
    Bethesda, MD 20817

ACLARK.NET, LLC will then PayPal $100 USD to David Schmidt in Germany, upon receipt of this check.

.. [1] http://en.wikipedia.org/wiki/Python_Imaging_Library
.. [2] Courtesy of http://pypi.python.org/pypi/vanity: Pillow has been downloaded 266,696 times!
.. [3] The Python Wall of SuperPowers reports over 50% of popular packages have been ported: https://python3wos.appspot.com/.
.. [4] http://dist.plone.org/thirdparty/PIL-1.1.7.tar.gz
.. [5] http://mail.python.org/pipermail/image-sig/2010-July/006423.html
.. [6] https://twitter.com/shimizukawa
.. [7] https://github.com/fluggo
.. [8] https://github.com/python-imaging/Pillow/issues/18#issuecomment-12023891
.. [9] https://fedoraproject.org/wiki/Features/Pillow
.. [10] Hopefully the PSF will be able to review my proposal before PyCon 2013. Regardless, I'll still be working on making the release deadline.
.. [11] https://github.com/python-imaging/Pillow/issues/61
