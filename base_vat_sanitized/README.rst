==================
Base VAT Sanitized
==================

.. !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fpartner--contact-lightgray.png?logo=github
    :target: https://github.com/OCA/partner-contact/tree/13.0/base_vat_sanitized
    :alt: OCA/partner-contact
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/partner-contact-13-0/partner-contact-13-0-base_vat_sanitized
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runbot-Try%20me-875A7B.png
    :target: https://runbot.odoo-community.org/runbot/134/13.0
    :alt: Try me on Runbot

|badge1| |badge2| |badge3| |badge4| |badge5| 

**THIS MODULE WAS PORTED TO ODOO 13.0 BY MISTAKE: DON'T INSTALL IT**. The feature is now native in Odoo 13.0 (it is implemented in the `base_vat <https://github.com/odoo/odoo/tree/13.0/addons/base_vat>`_ module).

This module adds a technical field *sanitized_vat* on partners that stores the VAT number
without spaces and with letters in uppercase. It is useful for other modules that need to
match partners on VAT number, such as the *base_business_document_import* module for example.

**Table of contents**

.. contents::
   :local:

Usage
=====

This module doesn't bring any visible feature for the users.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/partner-contact/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed
`feedback <https://github.com/OCA/partner-contact/issues/new?body=module:%20base_vat_sanitized%0Aversion:%2013.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Akretion

Contributors
~~~~~~~~~~~~

* Alexis de Lattre <alexis.delattre@akretion.com>
* Andrea Stirpe <a.stirpe@onestein.nl>
* Stephan Rozendaal <stephan.rozendaal@neobis.net>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/partner-contact <https://github.com/OCA/partner-contact/tree/13.0/base_vat_sanitized>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
