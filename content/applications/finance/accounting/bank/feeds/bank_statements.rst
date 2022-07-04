===============
Bank statements
===============

Importing your bank statements in Odoo Accounting allows you to keep track of the financial
movements that occur on your bank accounts and reconcile them with the transactions recorded in your
accounting.

We recommend using :doc:`bank_synchronization` for more efficiency. However, if you do not want to
use **bank synchronization** or if your bank is not a supported institution, other options exists:

- Import the bank statement files delivered by your bank
- Register the bank statements manually

Import bank statements files
============================

Odoo supports multiple file formats to import bank statements:

- SEPA recommended Cash Management format (CAMT.053)
- Comma-separated values (.CSV)
- Open Financial Exchange (.OFX)
- Quicken Interchange Format (.QIF)
- Belgium: Coded Statement of Account (.CODA)

To import a file, go to :menuselection:`Accounting --> Overview --> Bank`, click on
:guilabel:`Import Statements`, or on the ⋮ button and then on :guilabel:`Import Statement`.

.. image:: bank_statements/bank-overview.png
   :align: center
   :alt: Import a bank statement file in Odoo Accounting

Next, select the file you want to import and click on :guilabel:`Import`.

Odoo opens an **import widget** to help you set the **Formatting Options** and **map** the
different columns you want to import. You also have the possibility to **test** the bank statement
file before uploading it to your database.

.. image:: bank_statements/import-bank-statement.png
   :align: center
   :alt: Register bank statements manually in Odoo Accounting

.. note::
   Quicken Interchange Format (.QIF) is an older file format that is no longer supported since 2005. 
   If possible, prefer .OFX files over .QIF.

Register bank statements manually
=================================

If needed, you can also record your bank statements manually.

To do so, go to :menuselection:`Accounting --> Overview --> Bank`, click on
:guilabel:`Create Statements`, or on the ⋮ button and then on :guilabel:`New Statement`.

Add a new line for each transaction written on the original bank statement.

To ease the reconciliation process, make sure to fill out the **Partner** field. You can also type
in the payments’ references in the **Label** field.

.. image:: bank_statements/bank-statements-03.png
   :align: center
   :alt: Register bank statements manually in Odoo Accounting

.. note::
   The **Ending Balance** and the **Computed Balance** should have the same amount. If it is not the
   case, make sure that there is no mistake in the transactions’ amounts.

.. todo:: add doc link to new documentation about reconciliation
