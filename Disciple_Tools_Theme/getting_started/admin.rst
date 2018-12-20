Admin
*****

This is the wp-admin or backend of Disciple.Tools. Only certain roles within your Disciple.Tools instance will be able to access this and depending on their role, access will vary. 

To open up the admin backend, click on the |gear| on the top right and then click ``Admin``

To see what each role has access to, click `here <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/roles.html#roles>`_ 


Contacts
=======

These are the backend records of the contacts that can be found in the `Contact List Page <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/contacts.html#contacts-list-page>`_. Every Disciple.Tools user will also have a Contact Record made for them. We recommend you edit every `Contact Record <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/contacts.html#contacts-record-page>`_ on the front end.

You can delete a contact record by hovering over their name and clicking ``Trash``.

Groups
======

These are the backend records of the groups that can be found in the `Groups List Page <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/groups.html#groups-list-page>`_. We recommend you edit every `Group Record <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/groups.html#group-record-page>`_ on the front end.

You can delete a group record by hovering over their name and clicking ``Trash``.

Locations
========

Locations will not automatically show up in the frontend when editing a Contact or Group Record. You must first add locations in the Admin backend for them to show up as options for the frontend. 


All Locations
-------------

All of your added locations will be listed here. Click ``Add New`` to get started. 

When you hover over the name of a location, the following options appear:

- Edit
- Quick Edit
- Trash
- View

Edit Location
~~~~~~~~

Click on the name of the location or hover over it and click ``Edit``

More Documentation Coming Soon


Add New Location
--------

The location feature is still being developed. 

**To manually add locations:**

Add Countries

1. Add a country name in the text box that says ``Enter the location title here`` (E.g. France) and click ``Save``
2. Under Geo-Code, in the Address box, type in the name of the country. (E.g. France) and click ``Validate`` and then ``Save``
3. Repeat for every country you want as a location option

Add Regions/States/Provinces

1. Click ``Add New`` to add regions/states/provinces
2. Name the location using the name of a region/state/province (E.g. Île-de-France, France) and click ``Save``
3. Under Geo-Code, in the Address box, type in the name of the region/state/province. (E.g. Île-de-France, France).
4. Under Levels, change the ``Parent`` location to the country name (e.g. France) and click ``Save``.
5. Repeat for every region/state/province you want as a location option

Add Cities

1. Click ``Add New`` to add cities
2. Name the location using the name of a city (E.g. Paris, Île-de-France, France) and click ``Save``
3. Under Geo-Code, in the Address box, type in the name of the city. (E.g. Paris, France).
4. Under Levels, change the ``Parent`` location to the region/state/province (E.g. Île-de-France, France) and click ``Save``.
5. Repeat for every city you want as a location option



Import
------


This location feature is still being developed. 


People Groups
=============

Various people groups will not automatically show up in the frontend when editing a Contact or Group Record. You must first add the people groups in the Admin backend for them to show up as options for the frontend. 



All People Groups
---------------

All of your added people groups will be listed here. Click ``Add New`` to get started.  

When you hover over the name of a people group, the following options appear:

- Edit
- Quick Edit
- Trash
- View

Edit People Group
~~~~~~~~~~~

Click on the name of the people group or hover over it and click ``Edit``


Add New
-----

1. Under ``Add/Update People Group``, select a country to view its people groups and click ``Search``
2. Next to the people groups you want to add, click the ``link`` button. 
3. A note will appear that says "The current people group data has been updated with this info! Refresh to see data"

Import
-----

Documentation Coming Soon


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

Users can change their Site Notifications within their personal Profile Settings, but you have the ability to override this here. The boxes that are checked represent types of notifications that every Disciple.Tools user will be required to receive via Email and/or Web (the notification bell |Notification Bell|) . Unchecked boxes mean that the individual user will have the choice whether they want to receive that type of notification or not. 

**Types of Site Notifications:**

- Newly Assigned Contact
- @Mentions
- New comments
- Update Needed
- Contact Info Changed
- Contact Milestones and Group Health Metrics


Update Needed Triggers
~~~~~~~~

In order to prevent seekers from falling through the cracks, Disciple.Tools will notify users when Contact Records and Group Records need updating. 

**Contacts**

You can edit the frequency (by number of days) that this message will automatically be triggered in relation to where a contact is on their Seeker Path (i.e. First Meeting Complete). You an also change the comment that will appear in the message. Be sure to click ``Save`` to apply the change.

For example, a user has completed a first meeting with a contact and notes that within the Contact Record. If the user doesn't update this record after the chosen number of days, then the user will receive an alert within the Contact Record. Also, this Contact Record will be listed in the Filters section under ``Update Needed``. This will help Multipliers prioritize their contacts and provide a sense of accountability. The Dispatcher or the DT Admin can oversee the accountability piece to make sure that Multipliers are updating their Contact Records to the agreed upon time frame. 

An update constitutes as any change to the Contact Record that would be recorded in the Comment/Activity Tile.

Be sure to click the box ``Update needed triggers enabled`` if you want users to receive this alert message. 

**Groups**

You can edit the frequency (by number of days) that this message will automatically be triggered since the last time a Group Record was updated. You an also change the comment that will appear in the message.

An update constitutes as any change to the Group Record that would be recorded in the Comment/Activity Tile.

Be sure to click the box ``Update needed triggers enabled`` if you want users to receive this alert message. 


Custom Lists
--------------------

This page allows you to customize the following pre-existing fields

- User (Worker) Contact Profile
- Sources: Where contacts originate
- Contact Communication Channels aka Social Media


User (Worker) Contact Profile
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This represent fields the user's profile information that can be found under Profile by clicking the |gear| icon. 

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

These options represent the Social Media option that can be found in the `Contact Record Details Tile <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/contacts.html#details-tile>`_. 


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



Custom Tiles and Fields
------------------

A Tile is a section within the Contact/Group Record Pages (i.e. Details tile). A Tile is made up of Fields.

**Example Tile and Fields**

|English Club Tile|


This English Club Tile is made up of the following fields:

- English Club Pathway
- English CLub Start Date
- Interests
- Topics Completed

The Interests field, for example, is made up of the following options:

- Receive Bible
- Discuss Christianity
- Join a Bible Study
- Put on Newsletter List

Build a Complete Tile
~~~~~~~~~~~~~~~~

**Create a new tile:**

1. Click ``Add a new tile``
2. Select whether it will be found in the Contact or Group page type
3. Name it.
4. Click ``Create Tile``


**Create new fields**

1. Under ``Custom Fields``, click ``Create new field``
2. Select whether it will be found in the Contact or Group page type
3. Select the Field Type
 
- Dropdown: Select an option for a dropdown list
- Multi Select: A field like the milestones to track items like course progress
- Text: This is just a normal text field
- Date: A field that uses a date picker to choose dates (like baptism date)
 
4. Select the name of the new Tile you created 
5. Click ``Create Field``
6. Add the options for Dropdown and Multi Select fields

   a. Under ``Field Options``, next to ``Add new option``, insert the name of the option and click ``Add``
   b. Continue adding until you have all of your preferred options. 
   
7. Click ``Save``
8. Repeat steps 1-7 until you have all of your desired fields for the Tile


**Preview Tile**

Preview your Tile within the Contact or Group Record by returning to the frontend. Cick the |House| icon to return.

To modify the tile, fields, and options, click the |gear| icon and Admin to return to the backend.


Modify Tiles, Fields, and Options
~~~~~~~~~~~~~~~~~~

**Modify Tile**

Under Custom Tiles, next to ``Modify an existing tile``, select the name of the tile you want to modify

- Adjust the order of the fields by clicking the up and down arrows. 
- Rename the tile by changing the Label name under ``Tile Settings``
- Hide the tile by clicking ``Hide tile on page``


**Modify Field**

Under Custom Fields, next to ``Modify an existing field``, select the name of the field you want to modify


- Adjust the order of the field options by clicking the up and down arrows
- Hide the field options by clicking ``Hide``
- Rename the field by changing the Label name under ``Field Settings``


**Note:** You do not have the ability to modify every Disciple.Tools field. You, however, can modify any new field you create. The other default fields you can currently modify are:

Contact Fields:

- Overall Status
- Seeker Path
- Milestones
- Reason Not Ready
- Reason Paused
- Reason Closed

Group Fields:

- Group Type
- Church Health




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

Documentation Coming Soon

Appearance
==========

Documentation Coming Soon

Users
=======

Documentation Coming Soon

Tools
======

Documentation Coming Soon

Settings
=========

Documentation Coming Soon

Site Links
===========

Documentation Coming Soon







.. |System Email Subject Line| image:: /Disciple_Tools_Theme/images/system-email-subject.png
.. |Notification Bell| image:: /Disciple_Tools_Theme/images/Notification-bell.png
.. |gear| image:: /Disciple_Tools_Theme/images/Gear.png
.. |English Club Tile| image:: /Disciple_Tools_Theme/images/English-Club-Tile.png
.. |House| image:: /Disciple_Tools_Theme/images/House_Icon.png
