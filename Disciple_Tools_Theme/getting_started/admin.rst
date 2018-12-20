Admin
*****

This is the wp-admin or backend of Disciple.Tools. Only certain roles within your Disciple.Tools instance will be able to access this. To open up the admin backend, click on the ``gear`` on the top right and then click ``Admin``

Contacts
=======

These are the backend records of the contacts that can be found in the Contacts List Page. Every Disciple.Tools user will also have a Contact Record made for them. We recommend you edit every Contact Record on the front end.

You can delete a contact record by hovering over their name and clicking ``Trash``.

Groups
======

These are the backend records of the groups that can be found in the Groups List Page. We recommend you edit every Group Record on the front end.

You can delete a group record by hovering over their name and clicking ``Trash``.

Locations
========

Add New
--------

Import
------


People Groups
=============

Add New
-----

Import
-----


Extensions (DT)
==============

The Extensions page allows you to download our plugins and plugins we recommend but did not build.


How to Install
~~~~~~~

To install a plugin, click on ``Install`` under the ``Actions`` section.  Once this is done, click ``Activate`` to activate the plugin. Once installed, it will show ``Activated`` under the actions section.

Our Plugins
~~~~~~~~~~~

These are plugins we built for Disciple.Tools.  Currently, we have the following:

* ``Disciple Tools Facebook Integration`` - This extends the Disciple Tools system with Facebook integration.
* ``Disciple Tools Demo Content`` - This extends the Disciple Tools system for rapid content addition for training purposes.
* ``Disciple Tools Webform`` - This extends the Disciple Tools system with a web form leads collection.

Recommended Plugins
~~~~~~~~~~~~~~~~~~~

The are plugins we recommend, but did not develop:

* ``UpdraftPlus Backup/Restore`` - Backup and restore: take backups locally, or backup to Amazon S3, Dropbox, Google Drive, Rackspace, (S)FTP, WebDAV & email, on automatic schedules.
* ``Two Factor Authentication`` - Secure your WordPress login forms with two-factor authentication, including WooCommerce login forms    
* ``Inactive Logout`` - Inactive logout provides functionality to log out any idle users defined specified time showing a message. This works for the frontend as well.

Settings (DT)
=============

Only Admin, DT Amin, and Dispatcher roles have access to ``Settings (DT)``. What one changes in this section, changes settings for the all users within your Disciple.Tools instance. 

General Settings (DT)
---------------------

Base User
~~~~~~~~

A Base User is the catch-all account for orphaned contacts and other records to be assigned to. When contacts are created, for example, via the webform integration, the contacts will be assigned to the Base User by default. To be a Base User, the user must be an Administrator, Dispatcher, Multiplier, Digital Responder, or Strategist.

To change the Base User, click the dropdown box and select a different user, then click ``Update``


Email Settings
~~~~~~~~

When your Disciple.Tools instance sends out system emails to users, such as "Update on Contact #231" it will include the same beginning subject line for every email. This is so your users will be able to quickly recoginze what kind of email it is. To change the default from "Discple Tools" to an alternative phrase, type that in the box and click ``Update``.

In this example, the chosen beginning subject line is "D.T CRM". If you work in a security concerning region, consider using a phrase that would not cause your work issues due to email subject lines not being encrypted. 

|System Email Subject Line|


Site Notifications
~~~~~~~~

Users can change their Site Notifications within their persoal Profile Settings, but you have the ability to override this here. The boxes that are checked represent types of notifications that every Disciple.Tools user will be required to receive. Unchecked boxes mean that the individual user will have the choice whether they want to receive that notification or not. 

Update Needed Triggers
~~~~~~~~

In order to prevent seekers from falling through the cracks, Disciple.Tools will notify users when Contact Records and Group Recoreds need updating. 

**Contacts**

You can edit the frequency (by number of days) that this message will automatically be triggered in relation to where a contact is on their Seeker Path (i.e. First Meeting Complete). You an also change the comment that will appear in the message. Be sure to click ``Save`` to apply the change.

For example, a user has completed a first meeting with a contact and notes that within the Contact Record. If the user doesn't update this record after the chosen number of days, then the user will receive an alert within the Contact Record. Also, this Contact Record will be listed in the Filters section under ``Update Needed``. This will help Multipliers prioritize their contacts and provide a sense of accountability. The Dispatcher or the DT Admin can oversee the accountability piece to make sure that Multipliers are updating their Contact Records to the agreed upon time frame. 

An update constitutes as any change to the Contact Record that would be recorded in the Comment/Activity Tile.

Be sure to click the box ``Update needed triggers enabled`` if you want users to receive this alert message. 

**Groups**

You can edit the frequency (by number of days) that this message will automatically be triggered since the last time a Group Record was updated. You an also change the comment that will appear in the message.

An update constitutes as any change to the Group Record that would be recorded in the Comment/Activity Tile.

Be sure to click the box ``Update needed triggers enabled`` if you want users to receive this alert message. 


Custom List
--------------------

This page allows you to customize the following pre-existing fields


User (Worker) Contact Profile
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This is the Users' profile information that can be found in their Profile by clicking the Gear icon. 

Has the fields:

* ``Label`` - Is the name of the field.
* ``Type`` - Is the type of the field.

  Field types:
  
  - Phone
  - Email
  - Social
  - Address
  - Other
  
* ``Description`` - A description of the field.
* ``Enabled`` - Whether it is enabled or not.

Has the actions:

* ``Reset`` - Resets to the defaults.
* ``Delete`` - Clicking this deletes the field.
* ``Add`` - Adds a new field.
* ``Save`` - Saves the current changes.

Sources
~~~~~~~

Has the fields:

* ``Label`` - Is the name of the field. Clicking on it allows you to edit it.
* ``Enabled`` - Whether it is enabled or not.

Has the actions:

* ``Reset`` - Resets to the defaults.
* ``Delete`` - Clicking this deletes the field.
* ``Add`` - Adds a new field.
* ``Save`` - Saves the current changes.

Contact Communication Channels
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Has the fields:

* ``Label`` - Is the name of the field.
* ``Type`` - Is the type of the field.

  Field types:
  
  - Facebook
  - Twitter
  - Instagram
  - Skype
  - Other
  
Has the actions:

* ``Reset`` - Resets to the defaults.
* ``Delete`` - Clicking this deletes the field.
* ``Add New Channel`` - Adds a new field.
* ``Save`` - Saves the current changes.

Custom Fields
------------

Modify an existing field
~~~~~~~~~~~~~~~~~~~~~

**Contact Fields**
Overall Status
Milestones
Seeker Path
Reason Not Ready
Reason Paused
Reason Closed

**Group Fields**

Health


Create a new field
~~~~~~~~~~~~~~~~~

**Page Type**
**New Field Name**
**Field Type**
- Dropdown: Select an option for a dropdown list
- Multi Select: A field like the milestones to track items like course progress
- Text: This is just a normal text field
- Date: A field that uses a date picker to choose dates (like baptism date)
**Tile**

Custom Tiles
------------

A tile is a section within the Contact/Group Record Pages (i.e. Details tile). A tile contains various ``fields`` within it. 

**Create a new tile:**

1. Click ``Add a new tile``
2. Select whether it will be found in the Contact or Group page type
3. Name it.
4. Click ``Create Tile``

Options: You can later rename this tile or hide it by clicking ``Hide tile on page``


Google Map API
------------

Documentation Coming Soon

Site Link System
------------

Documentation Coming Soon

Network Dashboard
------------

Documentation Coming Soon

Critical Path
------------

Documentation Coming Soon

Network Dahsboard
------------

Documentation Coming Soon


Utilities (DT)
=============

Appearance
==========

Users
=======

Tools
======

Settings
=========

Site Links
===========







.. |System Email Subject Line| image:: /Disciple_Tools_Theme/images/system-email-subject.png
