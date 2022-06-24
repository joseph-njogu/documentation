=============
Bank accounts
=============

You can manage as many bank accounts as needed on your database. Configuring them well allows you to
have all your banking data up to date and ready for the reconciliation with your journal entries.

In Odoo Accounting app, each bank account is configured to have a dedicated journal set to post all
entries in a dedicated account.

.. note:: Whenever you add a bank account, a dedicated journal and a dedicated account are
   automatically created and configured.

Every bank journal is displayed by default on the :guilabel:`Accounting Dashboard` in the form of a
convenient card and includes action buttons.

UPDATE IT
.. image:: bank_accounts/bank_accounts_card.png
   :align: center
   :alt: Bank Journals Cards are displayed on the Accounting Overview in Odoo Accounting

.. _bank_accounts_add:

Add a new bank account
======================

You can either connect your bank account to your Odoo database, or configure your bank account
manually and :doc:`upload the bank statements manually <../feeds/bank_statements>`.

Bank synchronization
--------------------

Connect your bank account to your database and have your bank statements synced automatically.

To synchronize a new bank account, go to :menuselection:`Accounting --> Configuration --> Add a Bank
Account`. Select your bank in the list, click on :guilabel:`Connect` and follow the instructions
on-screen.

.. note::
   :doc:`Click here <../../bank/feeds/bank_synchronization>` for more information on bank
   synchronization.

Manual configuration
--------------------

If your bank institution can’t be synchronized automatically, or if you prefer not to sync it with
your database, you may also configure your bank account manually.

One bank journal is already created in your Odoo Accounting and is available from
:menuselection:`Configuration --> journals`. Open it to edit the different information related to
your bank account.

To add a new bank account manually, go to :menuselection:`Accounting ‣ Configuration` click on
:guilabel:`Add a Bank Account`, then on :guilabel:`Create it`, and fill out the form.

.. note::
   Odoo recognize your bank account type (e.g., IBAN) and enables some features accordingly.

.. _bank_accounts_configuration:

Advanced configuration
======================

To edit an existing bank account, go to :menuselection:`Accounting --> Configuration --> Journals`
and select the bank journal you want to modify.

If you need to edit the bank account details, go to the :guilabel:`Account number` field and click
on the *External Link* button next to the list arrow. There, you can edit the bank account's number,
Account Holder, Account Holder Name, and your Bank Institution's details by clicking on the
*External Link* next to the *Bank* field. These details are used to register some payments.

On the bank journal is mentioned the bank feeds:
Undefined yet (if you don’t know yet if you will sync your bank with Odoo or  not)
Import (CAMT,CODA, CSV, OFX, QIF) : if you decide to import your bank statement in Odoo via different format (define it in the accounting > configuration> settings)



