.. _gs-admin:

Admin
*****

.. _wpadmin:

This is the wp-admin or backend of Disciple.Tools. Only certain roles within your Disciple.Tools instance will be able to access this and depending on their role, access will vary.


To open up the admin backend, click on the |gear| on the top right and then click ``Admin``

To see what each role has access to, click :ref:`here <gs-roles>`


.. _wpadmin-contacts:

Contacts
========

|Contacts menu item|

**Description**
 These are the backend records of the contacts that can be found in the :ref:`Contact List Page <Contacts List Page>`. Every Disciple.Tools user will also have a Contact Record made for them.

.. note::
    We recommend you edit every :ref:`Contact Record <Contacts Record Page>` on the front end and not in the WP Admin area.

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Contacts``

.. note::
    You can delete a contact record by hovering over their name and clicking ``Trash``.



.. _wpadmin-groups:

Groups
======

|Groups menu item|

**Description**
 These are the backend records of the groups that can be found in the :ref:`Groups List Page <Groups List Page>`.

.. note::
 We recommend you edit every :ref:`Group Record <Group Record Page>` on the front end and not in the WP Admin area.

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Groups``.

.. note::
 You can delete a group record by hovering over their name and clicking ``Trash``.

.. _wpadmin-mapping:

Mapping
=======

|Mapping menu item|

.. Note::
 This section replaces the former Locations section that was migrated as of June 3rd, 2019.


.. _wpadmin-locations-migrate:

How to migrate old locations
----------------------------

**Step 1:** Make sure you have a back-up before doing a large data migration!

**Step 2:** From the front end of the system, click the |gear| in the upper right hand corner and select ``Admin``.

**Step 3:** Once you’re viewing the ``Admin`` back end of your site, select |Mapping menu item| in the menu on the left.

You will see several tabs starting with "General Settings" and "Mapping Focus" and "Migrating from Locations". "Mapping Focus" and "Migrating from Locations" are the two you need for now.

**Step 4** Click the ``Mapping Focus`` tab.

You will want to limit the mapping scope from “World” to your focus area, and this will limit the list of location choices to a manageable amount.  This may be a region of the world (many countries), a single country, or some specific part of a country (state and/or county level).  Click the dropdown from World and pick Country. The view will change to show a list of all countries and all will be checked.  It is probably easiest to click “unselect all” and then select the country or countries of focus.  When you have the country(ies) selected, click save.  If your focus is narrower than an entire country, you will want to drill down deeper and save at that level.

**Step 5** Now click on the tab ``Migrating from Locations``.

|Locations conversion|

Here, you will see a list of your existing locations and each will have ``World`` selected and a dropdown field next to it.  Under the column ``Select a Location`` click the dropdown and select the country that your location represents or the country the location would be found within.

After you click the country, a new dropdown field will appear. If the existing location is a state/province within the country, click the dropdown box again and select the appropriate state/province.

If the location is a county/municipality within the state/province, click the dropdown box again and select the appropriate county/municipality.

Once you have selected a new location that matches the existing location, look under the column ``Select option``, and choose ``Convert``.

If your location is more granular than the county/municipality level listed within GeoNames, click the other conversion option ``Create as sub-location`` to make your location a sub-location to the appropriate county. (e.g. Neighborhood)

If you have many locations, you can convert and save in batches, but you must click Save. Before clicking ``Save`` be sure your conversions are correct, because you CANNOT undo the conversion.

Only locations that are selected on contact and group records will be listed, so do not worry if several locations within your focus area do not appear in the list needing to be migrated.  You will only need to convert each of your locations once.  Once you’ve completed this step, the Migrating from Locations tab will disappear and you will be fully set up on the new locations structure.


.. _wpadmin-people-groups:

People Groups
=============

|People Groups menu item|

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

.. _people-group-filter:

Filter and Search People Groups
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
There is a people groups ``Filter`` facility at the top of the people groups list that can be used to find people groups. The filter uses the date the listing was added to your instance of DT.

You can also use the ``Search People Groups`` field on the top right side of this screen to find a people group that has already been added.

.. _people-group-edit:

Edit People Group
~~~~~~~~~~~~~~~~~~
Click on the name of the people group or hover over it and click ``Edit``

The numbers at the end of the people group such as the Bambara ( France | 100925 ), represents the ROP3 code. This code is a unique identifier shared between the list of people groups identified by Joshua Project and the IMB. When you import or link a people group with this ROP3 code, it will import data labels used by these two organizations for that people group. When you select a contact's people group in their Contact Record Details Tile, it will give the potential for reporting key metrics on the status of their people group. What God does among your people as noted in Disciple.Tools will be very helpful data for updating Joshua Project and IMB's databases on the status of the Great Commission.

.. _people-group-add:

Add New People Group
--------------------

.. Note:: We recommend importing rather than individually adding each people group one-by-one.

#. Name the People Group where it says ``Enter the people group title here`` (E.g. Bambara, France)
#. Under ``Add/Update People Group``, select a country to view its people groups and click ``Search`` (E.g. France) or if you know the **ROP3 Code**, then enter that in the other field, and then click ``Search``
#. Next to the people groups you want to add, click the ``link`` button. (e.g. Bambara)
#. A note will appear that says "The current people group data has been updated with this info! Refresh to see data".
#. Click ``Publish``


.. _people-group-import:

Import People Groups
--------------------
For a faster build of your people groups, import rather than add.

1. In the country drop down list, select a country (e.g. France)
2. Click the ``add`` button for each people group you want to add to your list
3. These will get added without having to click save. To view your list of people groups click ``All People Groups``

Note: The numbers at the end of the people group such as the Bambara ( France | 100925 ), represents the ROP3 code. This code is a unique identifier shared between the list of people groups identified by Joshua Project and the IMB.


.. _wpadmin-extensions-dt:

Extensions (DT)
===============

|Extensions (DT) menu item|

**Description**
 The Extensions page allows you to download our plugins and plugins we recommend but did not build.


.. _dt-plugins:

Plugins
-------

.. _dt-plugins-install:

How to Install
~~~~~~~~~~~~~~

1. To access the admin backend, click on the |gear| on the top right and click ``Admin``.
2. In the left hand column, select ``Plugins``.
3. To install a plugin, click on ``Install``. (Demo sites, skip to step 4.)
4. Once this is done, click ``Activate`` to activate the plugin. Once installed, it will show ``Activated`` under the actions section.

.. note:: Each pulgin/extension that is installed and activated will often have a menu item added to the list of ``Extensions``. Some but not all extensions will need configuring.

.. _dt-plugins-ours:

Our Plugins
~~~~~~~~~~~

These are plugins we built for Disciple.Tools.  Currently, we have the following:

* ``Disciple.Tools Genmapper`` - extends the Disciple.Tools system with visual generation mapping for groups and baptisms.
* ``Disciple.Tools Facebook Integration`` - This extends the Disciple Tools system with Facebook integration. When Facebook users private message your Facebook page, it automatically imports a contact record with the private message content. 
* ``Disciple.Tools Webform`` - This extends the Disciple Tools system with a web form leads collection.
* ``Disciple.Tools Demo Content`` - This extends the Disciple Tools system for rapid content addition for training purposes.
* ``Disciple.Tools Mobile App Extension`` - This lets you use the Disciple.Tools instances with the :ref:`DT mobile app <dt-app>`.


.. _dt-plugins-recommended:

Facebook Plugin
---------------

1. After you activate the Facebook plugin, under Extensions DT, click ``Facebook``. (If you don't see it, try refreshing the page)
2. Follow the instructions to configure the plugin.


Recommended Plugins
~~~~~~~~~~~~~~~~~~~

The are plugins we recommend, but did not develop:

* ``UpdraftPlus Backup/Restore`` - Backup and restore: take backups locally, or backup to Amazon S3, Dropbox, Google Drive, Rackspace, (S)FTP, WebDAV & email, on automatic schedules.
* ``Two Factor Authentication`` - Secure your WordPress login forms with two-factor authentication, including WooCommerce login forms
* ``Inactive Logout`` - Inactive logout provides functionality to log out any idle users defined specified time showing a message. This works for the frontend as well.



.. _wpadmin-settings-dt:

Settings (DT)
=============

|Settings (DT) menu item|


**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.

Only Admin, DT Amin, and Dispatcher roles have access to ``Settings (DT)``. What one changes in this section, changes settings for the all users within your Disciple.Tools instance.


.. _settings-dt-general:

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


.. _settings-dt-general-email:

Email Settings
~~~~~~~~~~~~~~

**Description**
 When your Disciple.Tools instance sends out system emails to users, such as "Update on Contact #231" it will include the same beginning subject line for every email. This is so your users will be able to quickly recognize what kind of email it is.

**How to access**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Scroll down to the section titled ``Email Settings``.
 4. To change the default from "Disciple Tools" to an alternative phrase, type that in the box and click ``Update``.

In this example, the chosen beginning subject line is "D.T CRM". If you work in a security concerning region, consider using a phrase that would not cause your work issues due to email subject lines not being encrypted.

|System Email Subject Line|

.. _settings-dt-general-notifications:

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

An update constitutes as any change to the :ref:`Contact Record <c-contacts-record-page>` that would be recorded in the :ref:`Comment/Activity Tile <c-comments-activity-tile>`.

Be sure to click the box ``Update needed triggers enabled`` if you want users to receive this alert message.

**Groups**

You can edit the frequency (by number of days) that this message will automatically be triggered since the last time a Group Record was updated. You an also change the comment that will appear in the message.

An update constitutes as any change to the :ref:`Group Record <g-group-record-page>` that would be recorded in the :ref:`Comment/Activity Tile <g-group-comments-and-activity-tile>`.

Be sure to click the box ``Update needed triggers enabled`` if you want users to receive this alert message.


Group Tile Preferences
~~~~~~~~~~~~~~~~~~~~~~

Here you can choose if you want some tiles to be displayed or not. The current tiles that are optional are:

    - Church Metrics
    - Four Fields

If you make changes, by ticking or un-ticking the option, ensure you click the ``Save`` button on the right side to ensure the changes are implemented.


.. _settings-dt-custom-lists:

Custom Lists
------------

**Description**
 This page allows you to customize the following pre-existing fields.

- User (Worker) Contact Profile
- Contact Communication Channels

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Click the tab titled ``Custom Lists``.


User (Worker) Contact Profile
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Description**
 This represents fields the user's profile information that can be found under ``Profile`` by clicking the |gear| icon.

Has the fields:

* ``Label`` - Is the name of the field.
* ``Type`` - Is the type of the field.

  Field types:

  - Phone
  - Email
  - Address
  - Phone work
  - Email work
  - Social
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


Contact Communication Channels
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Description**
 These options represent the Social Media channels that can be found in the :ref:`Contact Record Details Tile <c-details-tile>`. Add channels significant to the contacts in your field of work.


Has the fields:

* ``Label`` - Is the name of the field.
* ``Type`` - Is the type of the field.
* ``Icon link`` - link to where an icon file is stored.

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
* ``Enabled`` - Will be used/offered it box is selected.
* ``Hide domain if a url`` - Will truncate the URI to remove the domain.

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Click the tab titled ``Custom Lists``.
 4. Scroll down to section titled ``Contact Communication Channels``

.. _settings-dt-custom-tiles:

Custom Tiles
------------

**Description**
 This page allows you to create a new tile or modify existing tiles.


**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Click the tab titled ``Custom Tiles``.


Modify an existing tile
~~~~~~~~~~~~~~~~~~~~~~~
.. note:: The dropdown list will be empty if no custom tiles have been created for your instance of DT. Once one or more tiles have been created, then they will listed here and then be modifiable.

Choose an existing tile from the dropdown list (which are sorted into Contact Tiles and Group Tiles and People Group Tiles) then click ``Select``.

**Tile Settings**

* Change the name of the tile then click ``Save``
* Click ``Hide the tile on page`` if you do not want the tile to appear in the frontend.

**Tile Fields**

If there is more than one field in the custom tile you are modifying, then you will be able to change the order that the fields appear in. Use the |Arrows up and down| buttons to modify the order of the fields.

Create a new tile
~~~~~~~~~~~~~~~~~

#. Click the ``Add new tile`` button.
#. Select what type of page the tile will appear on: Contacts or Groups or People Groups.
#. Give the tile a name in the empty field next to ``New Tile Name``
#. Click ``Create tile``


.. _settings-dt-custom-fields:

Custom Fields
-------------

This page allows you to create a new field or modify existing fields.

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Click the tab titled ``Custom Fields``.

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

.. _build-a-tile:

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

Preview your tile within the Contact or Group Record by returning to the frontend. Click the |House| icon to return.

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


.. Note:: You do not have the ability to modify every Disciple.Tools field. You, however, can modify any new field you create. The other default fields you can currently modify are:

Contact Fields:

- Contact Status
- Seeker Path
- Faith Milestones
- Reason Not Ready
- Reason Paused
- Reason Closed
- Sources

Group Fields:

- Group Type
- Church Health

People Groups Fields: (coming soon!)






.. _wpadmin-site-link-system:

Site Link System
----------------

**Description**
 Site links are configured through the :ref:`Site Links System admin menu <wpadmin-site-links>`. The purpose of this is to link two Disciple Tools sites together in order to transfer contacts and share stats between the sites.

.. note:: The site link system is built to easily connect Disciple Tools systems together, but can be extended to provide token validation for other system integrations. Please refer to our `developer wiki <https://github.com/DiscipleTools/disciple-tools-theme/wiki/Site-to-Site-Link>`_ for more information.



**How to access:**
 #. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 #. In the left hand column, select ``Settings (DT)``.
 #. Click the tab titled ``Site Link System``.



.. _wpadmin-network-dashboard:

Network Dashboard
-----------------

**Description**
 Documentation Coming Soon

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Click the tab titled ``Network Dashboard``.


.. _wpadmin-security:

Security
--------

**Description**
 Here you can set some security headers for the Theme.

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Click the tab titled ``Security``.


.. note:: These security settings are enabled by default. We recommend leaving them enabled unless you run into any issues.


Enable and Configure Security Headers
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-    **X-XSS-Protection**:         Enable cross-site scripting filters.
-    **Referrer-Policy**:         Set Referrer Policy to "same-origin" to avoid leaking D.T activity.
-    **X-Content-Type-Options**:        Stops a browser from trying to MIME-sniff the content type.
-    **Strict-Transport-Security**:         Enforce the use of HTTPS.





.. _wpadmin-critical-path:

Critical Path
-------------

**Description**
 Documentation Coming Soon

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings (DT)``.
 3. Click the tab titled ``Critical Path``.








.. _wpadmin-reports-dt:

Reports (DT)
==============

|Reports (DT) menu item|

**Description**
 In this area of ``Reports (DT)`` you can access via tabs the areas of:

    Report List
        View reports or create a new report.

    Sources and Fields
        Add or Edit Custom metrics to track.


**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Reports (DT)``.



.. _wpadmin-utilities-dt:


Utilities (DT)
==============

|Utilities (DT) menu item|

**Description**
 In this area of ``Utilities (DT)`` you can access via tabs the areas of:

    Overview
        A summary of your WordPress version and PHP version.

    Field Explorer
        A list of all the fields available on this Instance.

    Import contacts
        Import contacts using the CSV file format.

    Import People groups
        Add a People Group using the country they are found in.


**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Utilities (DT)``.


.. _wpadmin-appearance:

Appearance
==========

|Appearance menu item|

**Description**
 In this area you can change the Theme, customize the theme, and edit the theme files.

.. note:: It is very unlikely that you will need to do anything in this area.

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Appearance``.


.. _wpadmin-users:

Users
=====

|Users menu item|

**Description**
 In this area you can view all the users in the system, add a new user, and access your profile.


.. note:: Refer to the :ref:`Users <gs-users>` section under Getting Started to learn how to use this area.

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Users``.

.. _wpadmin-tools:

Tools
=====

|Tools menu item|

**Description**
 Documentation Coming Soon

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Tools``.

.. _wpadmin-settings:

Settings
========

|Settings menu item|

**Description**
 In this area you can view and edit the settings for WordPress.

 #. General
 #. Writing
 #. Reading
 #. Discussion
 #. Media
 #. Permalinks
 #. Privacy

**How to access:**
 1. Access the admin backend by clicking on the |gear| on the top right and then click ``Admin``.
 2. In the left hand column, select ``Settings``.


.. _wpadmin-site-links:

Site Links
===========

The purpose of this is to link two Disciple Tools sites together in order to transfer contacts and share stats between the sites.

For example, a team in Spain receives a contact from Germany. The team in Spain can link their Disciple Tools site to their partner's site in Germany. They will be able to transfer any contacts from the Spain site to the Germany site and vice versa.

The visualization of the stats is still being developed. (Coming Soon!)

.. note:: The site link system is built to easily connect Disciple Tools systems together, but can be extended to provide token validation for other system integrations. Please refer to our `developer wiki <https://github.com/DiscipleTools/disciple-tools-theme/wiki/Site-to-Site-Link>`_ for more information.


Add New Site Link
-----------------

|Site Links menu item|

Before you get started, you need to be in the :ref:`admin backend <gs-admin>` and have clicked on ``Site Links``.

Phase 1: Setup Link from Site 1
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

|Site 1 link|


1. **Click "Add New":** Next to the title **Site Links** click the ```Add New`` button.
2. **Enter the title here:** Enter the name of the site you are linking to yours here.
3. **Token:** Copy the token code and securely send it to administrators of Site 2.
4. **Site 1:** Click ``add this site`` to add your site
5. **Site 2:** Add the url of the other site you are wanting to link with yours.
6. **Connection Type:**  Select the type of connection you (Site 1) wish to have with Site 2

- Create contacts
- Create and Update Contacts
- Contact Transfer Both Ways: Both sites with send and receive contacts from each other.
- Contact Transfer Sending Only: Site 1 will only send contacts to Site 2 but will not receive any contacts.
- Contact Transfer Receiving Only: Site 1 will only receive contacts from Site 2 but will not send any contacts.

7. **Configuration:** Ignore this section.
8. **Click Publish:** You (Site 1) will see the status as “Not Linked.” That is because the link needs to be also setup on the other site (Site 2).
9. **Inform admin of Site 2 to setup link:** You can send the link to the section below to give them instructions.


Phase 2: Setup Link from Site 2
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

|Site 2 link|


1. **Click Add New**
2. **Enter the title here:** Enter the name of the other site (Site 1).
3. **Token:** Paste the token shared by the admin of Site 1 here
4. **Site 1:** Add the url of Site 1
5. **Site 2:** Click ``add this site`` to add your site (Site 2)
6. **Connection Type:**  Select the type of connection you wish to have with Site 1

- Create contacts
- Create and Update Contacts
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
.. |Site 1 link| image:: /Disciple_Tools_Theme/images/Site-1-Link.png
.. |Site 2 link| image:: /Disciple_Tools_Theme/images/site-2-link.png
.. |Locations conversion| image:: /Disciple_Tools_Theme/images/locations-conversion.png
.. |Arrows up and down| image:: /Disciple_Tools_Theme/images/arrows-up-down.png


.. |Contacts menu item| image:: /Disciple_Tools_Theme/images/Contacts-wpadmin.png
.. |Groups menu item| image:: /Disciple_Tools_Theme/images/Groups-wpadmin.png
.. |Mapping menu item| image:: /Disciple_Tools_Theme/images/Mapping-wpadmin.png
.. |People Groups menu item| image:: /Disciple_Tools_Theme/images/People-Groups-wpadmin.png
.. |Extensions (DT) menu item| image:: /Disciple_Tools_Theme/images/Extensions-wpadmin.png
.. |Settings (DT) menu item| image:: /Disciple_Tools_Theme/images/Settings-DT-wpadmin.png
.. |Reports (DT) menu item| image:: /Disciple_Tools_Theme/images/Reports-wpadmin.png
.. |Utilities (DT) menu item| image:: /Disciple_Tools_Theme/images/Utilities-wpadmin.png
.. |Appearance menu item| image:: /Disciple_Tools_Theme/images/Appearance-wpadmin.png
.. |Users menu item| image:: /Disciple_Tools_Theme/images/Users-wpadmin.png
.. |Tools menu item| image:: /Disciple_Tools_Theme/images/Tools-wpadmin.png
.. |Settings menu item| image:: /Disciple_Tools_Theme/images/Settings-wpadmin.png
.. |Site Links menu item| image:: /Disciple_Tools_Theme/images/Site-Links-wpadmin.png
