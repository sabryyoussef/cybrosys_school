School
i upgrade this module from odoo 13 to 17 and 18
======

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |tech-docs| |odoo17-docs| |odoo18-docs| |help|
    * - tests
      - | |python37| |odoo17| |odoo18| |travis| |coverall|
    * - license
      - |github-license|
    * - contribute
      - |github-issues| |github-forks| |github-contributors|
    * - share
      - |share-twitter| |github-stars|

.. |tech-docs| image:: http://img.shields.io/badge/tutorial-docs-875A7B.svg?style=flat&colorA=8F8F8F
    :target: https://www.cybrosys.com/blog/how-to-create-module-in-odoo12
    :alt: Documentation Source

.. |odoo17-docs| image:: http://img.shields.io/badge/17.0-docs-875A7B.svg?style=flat&colorA=8F8F8F
    :target: https://www.odoo.com/documentation/17.0/index.html
    :alt: Odoo 17 Documentation

.. |odoo18-docs| image:: http://img.shields.io/badge/18.0-docs-875A7B.svg?style=flat&colorA=8F8F8F
    :target: https://www.odoo.com/documentation/18.0/index.html
    :alt: Odoo 18 Documentation

.. |help| image:: http://img.shields.io/badge/master-help-875A7B.svg?style=flat&colorA=8F8F8F
    :target: https://www.odoo.com/forum/help-1
    :alt: Odoo Help

.. |share-twitter| image:: https://img.shields.io/twitter/url?url=https%3A%2F%2Fgithub.com%2Fmacagua%2Fcybrosys_school
    :target: https://twitter.com/intent/tweet?text=Download%20and%20use%20%27cybrosys_school%27%20package%20for%20doing%20Python%20trainings%20in%20Venezuela%20%F0%9F%87%BB%F0%9F%87%AA%20https://github.com/macagua/cybrosys_school
    :alt: Share at Twitter

.. |github-contributors| image:: https://img.shields.io/github/contributors/macagua/cybrosys_school.svg
    :target: https://github.com/macagua/cybrosys_school/graphs/contributors
    :alt: Github Contributors

.. |github-license| image:: https://img.shields.io/github/license/macagua/cybrosys_school.svg
    :target: https://github.com/macagua/cybrosys_school/blob/master/LICENSE
    :alt: Github License

.. |github-issues| image:: https://img.shields.io/github/issues/macagua/cybrosys_school
    :target: https://github.com/macagua/cybrosys_school/issues
    :alt: Github Issues

.. |github-forks| image:: https://img.shields.io/github/forks/macagua/cybrosys_school
    :target: https://github.com/macagua/cybrosys_school/network/members
    :alt: Github Forks

.. |github-stars| image:: https://img.shields.io/github/stars/macagua/cybrosys_school
    :target: https://github.com/macagua/cybrosys_school/stargazers
    :alt: Github Favorites

.. |python37| image:: https://img.shields.io/badge/Python-3.7-blue
    :target: https://www.python.org/downloads/release/python-375/
    :alt: Python 3.7.5 version

.. |odoo17| image:: https://img.shields.io/badge/Odoo-17-blue
    :target: https://github.com/odoo/odoo/tree/17.0
    :alt: Odoo 17 version

.. |odoo18| image:: https://img.shields.io/badge/Odoo-18-blue
    :target: https://github.com/odoo/odoo/tree/18.0
    :alt: Odoo 18 version

.. |travis| image:: https://travis-ci.org/macagua/cybrosys_school.svg?branch=master
    :target: https://travis-ci.org/macagua/cybrosys_school
    :alt: Travis-CI Build Status

.. |coverall| image:: https://coveralls.io/repos/github/macagua/cybrosys_school/badge.svg?branch=master
    :target: https://coveralls.io/github/macagua/cybrosys_school?branch=master
    :alt: Coveralls Checkout Status

.. end-badges


About
=====

School is an Odoo module that lets you:

- Manage Students Information.
- Supports Odoo versions 13, 17, and 18.


Features
========

This Odoo module includes the following technical features:

- Data demonstration support.
- Internationalisation (i18n) support.
- Tests units support.
- ACL customisation support.


Dependencies
============

This module requires the following dependencies:

- odoo 13, 17, and 18 > https://github.com/odoo/odoo


Install
=======

Download the source code:

::

    $ git clone https://github.com/macagua/cybrosys_school.git


Move ``cybrosys_school`` folder into ``extra-addons`` Odoo directory:

::

    $ mv cybrosys_school /full/path/to/extra-addons/


Restart the Odoo instance server, log in and go to **Apps** > **School** > **Install**

.. figure:: https://raw.githubusercontent.com/macagua/cybrosys_school/master/static/description/install_module.png
    :align: center
    :width: 70%
    :alt: Install 'School' Module

    Install 'School' Module

Then go to the main menu at the top-left corner and click **School** > **Students**. Click the **Edit** button to edit an existing student or click **Create** to add a new student.

.. figure:: https://raw.githubusercontent.com/macagua/cybrosys_school/master/static/description/manage_app.png
    :align: center
    :width: 70%
    :alt: Access 'Manage Students' from School App

    Access 'Manage Students' from School App


Testing
=======

To run the module tests, use the following command:

::

    $ /full/path/to/odoo-bin --addons-path=/full/path/to/addons,/full/path/to/extra-addons \
      -d t -i cybrosys_school --test-enable --stop-after-init --log-level=test


Contribute
==========

- Issue Tracker: https://github.com/macagua/cybrosys_school/issues

- Source Code: https://github.com/macagua/cybrosys_school


License
=======

- This project is licensed under the AGPL-3.


References
==========

The following links were used as references for developing and upgrading this Odoo module:

Development
-----------

- `How to Create a Module in Odoo 12 <https://www.cybrosys.com/blog/how-to-create-module-in-odoo12>`_.
- `How to Create Module in Odoo v12 - Search View and Filters <https://www.cybrosys.com/blog/building-module-in-odoo-v12-defining-search-view-and-filters>`_.
- `How to Create Module in Odoo 12 - Defining the Views <https://www.cybrosys.com/blog/how-to-create-module-in-odoo-v12-defining-views>`_.
- `How to Add Chatter to Form View in Odoo v12 <https://www.cybrosys.com/blog/how-to-add-chatter-to-form-view-in-odoo-v12>`_.
- `How to Add Custom Fields to Existing Views in Odoo v12 <https://www.cybrosys.com/blog/adding-custom-fields-to-existing-views-in-odoo-v12>`_.
- `How to Define Header, Statusbar, and Buttons in Odoo v12 <https://www.cybrosys.com/blog/defining-header-statusbar-and-buttons-in-odoo-v12>`_.
- Added support for Odoo 17 and 18 versions as part of the upgrade.

Quality assurance
-----------------

- `Automated testing in Odoo <https://www.surekhatech.com/blog/automated-testing-in-odoo>`_.
- `Odoo Experience 2018 - Improve the Quality of Your Modules with Automated Tests <https://www.youtube.com/watch?v=jZddEWFdUcM>`_.

Translations
------------

- `Language Translation in Odoo 12 <https://www.cybrosys.com/blog/language-translation-odoo-12>`_.
- `How to load translations in Odoo <https://www.youtube.com/watch?v=ce5zMG7EGtE>`_.
