Admin
*****

This is the wp-admin or backend of Disciple.Tools. Only certain roles within your Disciple.Tools instance will be able to access this and depending on their role, access will vary.

To open up the admin backend, click on the |gear| on the top right and then click ``Admin``

To see what each role has access to, click `here <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/roles.html#roles>`_


Contacts
========

|Contacts-wpadmin|

**Description**
 These are the backend records of the contacts that can be found in the `Contact List Page <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/contacts.html#contacts-list-page>`_. Every Disciple.Tools user will also have a Contact Record made for them. We recommend you edit every `Contact Record <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/contacts.html#contacts-record-page>`_ on the front end.

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Contacts``

Note: You can delete a contact record by hovering over their name and clicking ``Trash``.

Groups
======

|Groups-wpadmin|

**Description**
 These are the backend records of the groups that can be found in the `Groups List Page <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/groups.html#groups-list-page>`_. We recommend you edit every `Group Record <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/groups.html#group-record-page>`_ on the front end.

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Groups``.

Note: You can delete a group record by hovering over their name and clicking ``Trash``.

Locations
=========

Locations has been migrated to the section called Mapping as of June 3rd, 2019.




Mapping
=======

|Mapping-wpadmin|

This section replaces the former Locations section.


How to migrate old locations
----------------------------


**Step 1:** Make sure you have a back-up before doing a large data migration!

**Step 2:** From the front end of the system, click the |gear| in the upper right hand corner and select ``Admin``.

**Step 3:** Once you’re viewing the ``Admin`` back end of your site, select |Mapping-wpadmin| in the menu on the left.


You will see several tabs starting with "General Settings" and "Mapping Focus" and "Migrating from Locations".  "Mapping Focus" and "`Migrating from Locations" are the two you need for now.

**Step 4** Click the ``Mapping Focus`` tab.

You will want to limit the mapping scope from “World” to your focus area, and this will limit the list of location choices to a manageable amount.  This may be a region of the world (many countries), a single country, or some specific part of a country (state and/or county level).  Click the dropdown from World and pick Country. The view will change to show a list of all countries and all will be checked.  It is probably easiest to click “unselect all” and then select the country or countries of focus.  When you have the country(ies) selected, click save.  If your focus is narrower than an entire country, you will want to drill down deeper and save at that level.

**Step 5** Now click on the tab ``Migrating from Locations``.

|locations-conversion|

Here, you will see a list of your existing locations and each will have ``World`` selected and a dropdown field next to it.  Under the column ``Select a Location`` click the dropdown and select the country that your location represents or the country the location would be found within.

After you click the country, a new dropdown field will appear. If the existing location is a state/province within the country, click the dropdown box again and select the appropriate state/province.

If the location is a county/municipality within the state/province, click the dropdown box again and select the appropriate county/municipality.

Once you have selected a new location that matches the existing location, look under the column ``Select option``, and choose ``Convert``.

If your location is more granular than the county/municipality level listed within GeoNames, click the other conversion option ``Create as sub-location`` to make your location a sub-location to the appropriate county. (e.g. Neighborhood)

If you have many locations, you can convert and save in batches, but you must click Save. Before clicking ``Save`` be sure your conversions are correct, because you CANNOT undo the conversion.

Only locations that are selected on contact and group records will be listed, so do not worry if several locations within your focus area do not appear in the list needing to be migrated.  You will only need to convert each of your locations once.  Once you’ve completed this step, the Migrating from Locations tab will disappear and you will be fully set up on the new locations structure.



People Groups
=============

|People-Groups-wpadmin|

**Description**
 Various people groups will not automatically show up in the frontend when editing a Contact or Group Record. You must first add the people groups in the Admin backend for them to show up as options for the frontend.

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``People Groups``.


All People Groups
-----------------

All of your added people groups will be listed here.

To get started, we recommend clicking ``Import`` for a faster experience. You can also manually add people groups by clicking ``Add New``

When you hover over the name of a people group, the following options appear:

- Edit
- Quick Edit
- Trash
- View

Edit People Group
~~~~~~~~~~~~~~~~~~~~~~

Click on the name of the people group or hover over it and click ``Edit``

The numbers at the end of the people group such as the Bambara ( France | 100925 ), represents the ROP3 code. This code is a unique identifier shared between the list of people groups identified by Joshua Project and the IMB. When you import or link a people group with this ROP3 code, it will import data labels used by these two organizations for that people group. When select a contact's people group in their Contact Record Details Tile, it will give the potential for reporting key metrics on the status of their people group. What God does among your people as noted in Disciple.Tools will be very helpful data for updating Joshua Project and IMB's databases on the status of the Great Commission.


Add New
-------

**Note:** We recommend importing rather than adding.

1. Name the People Group (E.g. Bambara, France)
2. Under ``Add/Update People Group``, select a country to view its people groups and click ``Search`` (E.g. France)
3. Next to the people groups you want to add, click the ``link`` button. (e.g. Bambara)
4. A note will appear that says "The current people group data has been updated with this info! Refresh to see data"
5. Click ``Publish``

Import
------

For a faster build of your people groups, import rather than add.

1. In the country drop down list, select a country (e.g. France)
2. Click the ``add`` button for each people group you want to add to your list
3. These will get added without having to click save. To view your list of people groups click ``All People Groups``

Note: The numbers at the end of the people group such as the Bambara ( France | 100925 ), represents the ROP3 code. This code is a unique identifier shared between the list of people groups identified by Joshua Project and the IMB.


Extensions (DT)
===============

|Extensions-wpadmin|

**Description**
 The Extensions page allows you to download our plugins and plugins we recommend but did not build.

Plugins
----------

How to Install
~~~~~~~~~~~~~~

1. To access the admin backend, click on the |gear| on the top right and click ``Admin``.
2. In the left hand column, select ``Plugins``.
3. To install a plugin, click on ``Install`` under the ``Actions`` section.
4. Once this is done, click ``Activate`` to activate the plugin. Once installed, it will show ``Activated`` under the actions section.

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

.. _settings-dt-wpadmin:
Settings (DT)
=============

|DT-Settings-wpadmin|


**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.

Only Admin, DT Amin, and Dispatcher roles have access to ``Settings (DT)``. What one changes in this section, changes settings for the all users within your Disciple.Tools instance.

General Settings (DT)
---------------------

Base User
~~~~~~~~~

**Description**
 A Base User is the catch-all account for orphaned contacts and other records to be assigned to. When contacts are created, for example, via the webform integration, the contacts will be assigned to the Base User by default. To be a Base User, the user must be an Administrator, Dispatcher, Multiplier, Digital Responder, or Strategist.

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Scroll down to the section titled ``Base User``.
 4. To change the Base User, click the dropdown box and select a different user, then click ``Update``


Email Settings
~~~~~~~~~~~~~~

**Description**
 When your Disciple.Tools instance sends out system emails to users, such as "Update on Contact #231" it will include the same beginning subject line for every email. This is so your users will be able to quickly recoginze what kind of email it is.

**How to access**

 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Scroll down to the section titled ``Email Settings``.
 4. To change the default from "Disciple Tools" to an alternative phrase, type that in the box and click ``Update``.

In this example, the chosen beginning subject line is "D.T CRM". If you work in a security concerning region, consider using a phrase that would not cause your work issues due to email subject lines not being encrypted.

|System Email Subject Line|


Site Notifications
~~~~~~~~~~~~~~~~~~

**Description**
 Users can change their Site Notifications within their personal Profile Settings, but you have the ability to override this here. The boxes that are checked represent types of notifications that every Disciple.Tools user will be required to receive via Email and/or Web (the notification bell |Notification Bell|) . Unchecked boxes mean that the individual user will have the choice whether they want to receive that type of notification or not.

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Scroll down to the section titled ``Site Notifications``.


**Types of Site Notifications:**

- Newly Assigned Contact
- @Mentions
- New comments
- Update Needed
- Contact Info Changed
- Contact Milestones and Group Health Metrics


Update Needed Triggers
~~~~~~~~~~~~~~~~~~~~~~

**Description**
 In order to prevent seekers from falling through the cracks, Disciple.Tools will notify users when Contact Records and Group Records need updating.

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Scroll down to the section titled ``Update Needed Triggers``.

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
------------

**Description**
 This page allows you to customize the following pre-existing fields

- User (Worker) Contact Profile
- Contact Communication Channels aka Social Media

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Click the tab titled ``Custom Lists``.




User (Worker) Contact Profile
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Description**
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

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Click the tab titled ``Custom Lists``.
 4. Locate section titled ``User (Worker) Contact Profile``

Sources
~~~~~~~

**Description**

The sources are a list of places that potential contacts could come from (i.e. Facebook, English Club)
Has the fields:

* ``Label`` - Is the name of the field. Clicking on it allows you to edit it.
* ``Enabled`` - Whether it is enabled or not.

Has the actions:

* ``Reset`` - Resets to the defaults.
* ``Delete`` - Clicking this deletes the field.
* ``Add`` - Adds a new field.
* ``Save`` - Saves the current changes.

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Click the tab titled ``Custom Lists``.
 4. Scroll down to section titled ``Sources``

Contact Communication Channels
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Description**
 These options represent the Social Media channels that can be found in the `Contact Record Details Tile <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/contacts.html#details-tile>`_. Add channels significant to the contacts in your field of work.


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

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Click the tab titled ``Custom Lists``.
 4. Scroll down to section titled ``Contact Communication Channels``



Custom Tiles and Fields
-----------------------

**Description**
 A Tile is a section within the Contact/Group Record Pages (i.e. Details tile). A Tile is made up of Fields.

**Example Tile and Fields**

|English Club Tile|


This English Club Tile is made up of the following fields:

- English Club Pathway
- English Club Start Date
- Interests
- Topics Completed

The Interests field, for example, is made up of the following options:

- Receive Bible
- Discuss Christianity
- Join a Bible Study
- Put on Newsletter List

Build a Complete Tile
~~~~~~~~~~~~~~~~~~~~~

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Click the tab titled ``Custom Tiles``.

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
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

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



Site Link System
----------------

**Description**
Documentation Coming Soon

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Click the tab titled ``Site Link System``.

Network Dashboard
-----------------

**Description**
Documentation Coming Soon

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Click the tab titled ``Network Dashboard``.

Critical Path
-------------

**Description**
Documentation Coming Soon

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Click the tab titled ``Critical Path``.



Utilities (DT)
==============

|Utilities-wpadmin|

**Description**
Documentation Coming Soon

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Utilities (DT)``.


Appearance
==========

|Appearance-wpadmin|

**Description**
Documentation Coming Soon

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Appearance``.

Users
=====

|Users-wpadmin|

Refer to the `Users <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/users.html#users>`_ section under Getting Started.

Tools
=====

|tools-wpadmin|

**Description**
Documentation Coming Soon

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Tools``.

Settings
========

|Settings-wpadmin|

**Description**
Documentation Coming Soon

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings``.

Site Links
===========


The purpose of this is to link two Disciple Tools sites together in order to transfer contacts and share stats between the sites.

For example, a team in Spain receives a contact from Germany. The team in Spain can link their Disciple Tools site to their partner's site in Germany. They will be able to transfer any contacts from the Spain site to the Germany site and vice versa.

The visualization of the stats is still being developed. (Coming Soon!)


Add New Site Link
-----------------

|Site-Links-wpadmin|

Before you get started, you need to be in the `admin backend <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/admin.html#admin>`_ and have clicked on ``Site Links``.

Phase 1: Setup Link from Site 1
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

|Site-1-Link|


1. **Click Add New**
2. **Enter the title here:** Enter the name of the site you are linking to yours here.
3. **Token:** Copy the token code and securely send it to administrators of Site 2.
4. **Site 1:** Click ``add this site`` to add your site
5. **Site 2:** Add the url of the other site you are wanting to link with yours.
6. **Connection Type:**  Select the type of connection you (Site 1) wish to have with Site 2

- Contact Transfer Both Ways: Both sites with send and receive contacts from each other.
- Contact Transfer Sending Only: Site 1 will only send contacts to Site 2 but will not receive any contacts.
- Contact Transfer Receiving Only: Site 1 will only receive contacts from Site 2 but will not send any contacts.

7. **Configuration:** Ignore this section.
8. **Click Publish:** You (Site 1) will see the status as “Not Linked.” That is because the link needs to be also setup on the other site (Site 2).
9. **Inform admin of Site 2 to setup link:** You can send the link to the section below to give them instructions.


Phase 2: Setup Link from Site 2
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

|Site-2-Link|


1. **Click Add New**
2. **Enter the title here:** Enter the name of the other site (Site 1).
3. **Token:** Paste the token shared by the admin of Site 1 here
4. **Site 1:** Add the url of Site 1
5. **Site 2:** Click ``add this site`` to add your site (Site 2)
6. **Connection Type:**  Select the type of connection you wish to have with Site 1

- Contact Transfer Both Ways: Both sites with send and receive contacts from each other.
- Contact Transfer Sending Only: Site 2 will only send contacts to Site 1 but will not receive any contacts.
- Contact Transfer Receiving Only: Site 2 will only receive contacts from Site 1 but will not send any contacts.

7. **Configuration:** Ignore this section.
8. **Click Publish:** Both Site 1 and Site 2 should see the status as “Linked”







.. |System Email Subject Line| image:: /Disciple_Tools_Theme/images/system-email-subject.png
.. |Notification Bell| image:: /Disciple_Tools_Theme/images/Notification-bell.png
.. |gear| image:: /Disciple_Tools_Theme/images/Gear.png
.. |English Club Tile| image:: /Disciple_Tools_Theme/images/English-Club-Tile.png
.. |House| image:: /Disciple_Tools_Theme/images/House_Icon.png
.. |Appearance-wpadmin| image:: /Disciple_Tools_Theme/images/Appearance-wpadmin.png
.. |Contacts-wpadmin| image:: /Disciple_Tools_Theme/images/Contacts-wpadmin.png
.. |DT-Settings-wpadmin| image:: /Disciple_Tools_Theme/images/DT-Settings-wpadmin.png
.. |Extensions-wpadmin| image:: /Disciple_Tools_Theme/images/Extensions-wpadmin.png
.. |Groups-wpadmin| image:: /Disciple_Tools_Theme/images/Groups-wpadmin.png
.. |Locations-wpadmin| image:: /Disciple_Tools_Theme/images/Locations-wpadmin.png
.. |People-Groups-wpadmin| image:: /Disciple_Tools_Theme/images/People-Groups-wpadmin.png
.. |Site-Links-wpadmin| image:: /Disciple_Tools_Theme/images/Site-Links-wpadmin.png
.. |Settings-wpadmin| image:: /Disciple_Tools_Theme/images/Settings-wpadmin.png
.. |Users-wpadmin| image:: /Disciple_Tools_Theme/images/Users-wpadmin.png
.. |Utilities-wpadmin| image:: /Disciple_Tools_Theme/images/Utilities-wpadmin.png
.. |tools-wpadmin| image:: /Disciple_Tools_Theme/images/tools-wpadmin.png
.. |Site-1-Link| image:: /Disciple_Tools_Theme/images/Site-1-Link.png
.. |Site-2-Link| image:: /Disciple_Tools_Theme/images/site-2-link.png
.. |Mapping-wpadmin| image:: /Disciple_Tools_Theme/images/Mapping-wpadmin.png
.. |locations-conversion| image:: /Disciple_Tools_Theme/images/locations-conversion.png
