Users
=====


Only Users with the role `DT Admin` can manage other users. Managing users includes inviting, creating, updating and deleting users.

Inviting Users
--------------
Here is how you invite someone to be a user within Disciple.Tools

1. Open the wp-admin page by clicking ``Admin`` from the Settings |Gear| in the top right of the page

2. Click the ``Users`` tab on the left. Next, click ``Add New``. 

.. note:: If you have a multisite you will have two options, ``Add Existing User`` and ``Add New User``. If you have a single site you will only have one option, ``Add New User``.

**Add Existing User**

If you want to add an existing user from another site, enter the user's email and click ``Add Existing User``.

**Add New User**

If the user does not already exist or you only have the 'Add New User option', fill out the required info and click the ``Add New User`` button. To learn more about User Roles, see `Roles`_.

.. note:: If there is already a Contact Record in your Disciple.Tools system that represents the user you want to add, then search for that contact's name in the ``Corresponds to Contact`` box. If the user is already a contact in the system, see the section "Inviting a user from a Contact Record" below.




Inviting a user from a Contact Record
------------------------------------
If there is already a contact record for the user you want to add, there is an easy option. In the Contact Record, click the ``Dispatcher actions`` dropdown menu on the top, left. Then click ``Make a user from this contact``. Add the User's email, change the display name if needed and then click ``Create user``.


Linking an existing contact to a user
--------------------------------------
If you realize that you have a contact that should be linked with a user account, then in the Contact Record click the ``Dispatcher actions`` dropdown menu on the top left. Then click ``Link to an existing user``.

.. target-notes::

.. _`Roles`: https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/dt_manual/roles.html

.. |Gear| image:: /Disciple_Tools_Theme/images/Gear.png
