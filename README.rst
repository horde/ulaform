==================
 What is Ulaform?
==================

:Contact: horde@lists.horde.org

.. contents:: Contents
.. section-numbering::

Ulaform is a PHP-based dynamic HTML form creation and generation
system. Ulaform allows users to create sophisticated forms using a web browser,
and then render the forms within other web pages by a simple PHP include inside
a <?php ... ?> tag, or in other Horde applications through the Horde Block api.
Ulaform is intended to replace other dynamic form generation techniques (such
as FrontPage forms which require the FrontPage extensions on the server, or CGI
scripts which require some programming ability).

Ulaform is based on the Horde_Form library of the Horde framework. This gives
it some useful capabilities: the ability to automatically validate data, using
JavaScript if available (or re-rendering of the form if not); the ability to
use GET or POST transparently; and others.

This software is OSI Certified Open Source Software. OSI Certified is a
certification mark of the `Open Source Initiative`_.

.. _`Open Source Initiative`: http://www.opensource.org/


Obtaining Ulaform
=================

Further information on Ulaform and the latest version can be obtained at

  http://www.horde.org/apps/ulaform


Documentation
=============

The following documentation is available in the Ulaform distribution:

:README_:           This file
:LICENSE_:          Copyright and license information
:`doc/CHANGES`_:    Changes by release
:`doc/CREDITS`_:    Project developers
:`doc/INSTALL`_:    Installation instructions and notes


Installation
============

Instructions for installing Ulaform can be found in the file INSTALL_ in the
``doc/`` directory of the Ulaform distribution.


Assistance
==========

If you encounter problems with Ulaform, help is available!

The Horde Frequently Asked Questions List (FAQ), available on the Web at

  http://wiki.horde.org/FAQ

Horde LLC runs a number of mailing lists, for individual applications
and for issues relating to the project as a whole. Information, archives, and
subscription information can be found at

  http://www.horde.org/community/mail

Lastly, Horde developers, contributors and users also make occasional
appearances on IRC, on the channel #horde on the Freenode Network
(irc.freenode.net).


Licensing
=========

For licensing and copyright information, please see the file LICENSE_ in the
Ulaform distribution.

Thanks,

The Ulaform team


.. _README: README.rst
.. _LICENSE: http://www.horde.org/licenses/gpl
.. _doc/CHANGES: doc/CHANGES
.. _doc/CREDITS: doc/CREDITS.rst
.. _INSTALL:
.. _doc/INSTALL: doc/INSTALL.rst
