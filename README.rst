Vtiger CRM - An enterprise-class CRM and more!
===================================================

**`Vtiger CRM - Open Source version`_**

* End to end sales cycle management from campaigns, leads, potentials, quotes, invoices..
* Support automation using a customer portal and support tickets
* Data import & export via CSV files, web-to-lead forms, reports & customizable user dashboards
* Role based access control
* Mobile applications
* Workflows, tasks, and project management
* Outlook, Thunderbird, Firefox, & Gmail plugins
* Extensions marketplace for additional plugins

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- Vtiger CRM configurations:
   
    - Installed from upstream source code to /var/www/vtigercrm

      See `Vtiger CRM documentation - Installation`_ for details.

      **Security note**: Updates to Vtiger CRM may require supervision so
      they **ARE NOT** configured to install automatically. See `Vtiger CRM documentation - Migration/upgrade`_ for upgrading.

- SSL support out of the box.
- `Adminer`_ administration frontend for MySQL (listening on port
  12322 - uses SSL).
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring Apache2, PHP, MySQL and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL: username **root**
-  Adminer: username **adminer**
-  Vtiger CRM: username **admin**


.. _Vtiger CRM - Open Source version: https://www.vtiger.com/it/open-source-crm/
.. _TurnKey Core: https://www.turnkeylinux.org/core
.. _Vtiger CRM documentation - Installation: https://community.vtiger.com/help/vtigercrm/administrators/installation.html
.. _Vtiger CRM documentation - Migration/upgrade: https://community.vtiger.com/help/vtigercrm/administrators/migration.html
.. _Adminer: https://www.adminer.org

