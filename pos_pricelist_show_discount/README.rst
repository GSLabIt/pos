================================
PoS show discount from pricelist
================================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:4e610cd951c1c60401f42f00ffdb77c16da29cfd2672cedadf5da4cde02cc6ff
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fpos-lightgray.png?logo=github
    :target: https://github.com/OCA/pos/tree/14.0/pos_pricelist_show_discount
    :alt: OCA/pos
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/pos-14-0/pos-14-0-pos_pricelist_show_discount
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/pos&target_branch=14.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|


This module allows to display in POS interface the discount applied to customer, calculated as difference between POS final price and price from a specific pricelist set in POS configuration.


This can be useful to provide customer an explicit reference of the discount applied from a "standard" pricelist, without the need to have the the POS pricelist based on the "standard" pricelist.

**Table of contents**

.. contents::
   :local:

Configuration
=============

Set the discount pricelist to use as reference in the pos configuration page.

Usage
=====

In general configuration, enable Pricelists

In POS configuration:

- enable "Advanced Pricelists" and add your reference pricelist to "Available pricelists"

- enable "Display Discount From Reference Pricelist" and select a reference pricelist


In POS interface, reference pricelist price and discount applied is displayed if POS price is lower than reference pricelist price.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/pos/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/pos/issues/new?body=module:%20pos_pricelist_show_discount%0Aversion:%2014.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Ooops404
* PyTech SRL
* Akretion

Contributors
~~~~~~~~~~~~

* Ooops404 <info@ooops404.com>

* PyTech SRL <info@pytech.it>

  * Alessandro Uffreduzzi <alessandro.uffreduzzi@pytech.it>

* Akretion

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-aleuffre| image:: https://github.com/aleuffre.png?size=40px
    :target: https://github.com/aleuffre
    :alt: aleuffre
.. |maintainer-pytech-bot| image:: https://github.com/pytech-bot.png?size=40px
    :target: https://github.com/pytech-bot
    :alt: pytech-bot

Current `maintainers <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-aleuffre| |maintainer-pytech-bot| 

This module is part of the `OCA/pos <https://github.com/OCA/pos/tree/14.0/pos_pricelist_show_discount>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
