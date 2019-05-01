Users
=====

Disciple.Tools is a collaborative software that can be modified and updated by multiple users at once. Each user has his or her own login and password. Each user is assigned a particular role allowing varying degrees of access to the Disciple.Tools site.

The only way a user can be added to Disciple.Tools is if the site `DT admin` invites him or her.

Inviting Users
--------------
Here is how a `DT admin` invites someone to be a user within Disciple.Tools:

1. In your Disciple.Tools site, click on the |Gear| in the top right of the page, then click ``Admin``. This will open the wp-admin page (backend of the site).

2. Click the ``Users`` tab on the left. Next, click the ``Add New``button. 

.. note:: If you have a multisite you will have two options, ``Add Existing User`` and ``Add New User``. If you have a single site you will only have one option, ``Add New User``.

Add Existing User
^^^^^^^^^^^^^^^^^
If you want to add an existing user from another site, enter the user's email and click ``Add Existing User``.

|existinguser|

.. note:: If there is already a Contact Record in your Disciple.Tools system that represents the user you want to add, then search for that contact's name in the ``Corresponds to Contact`` box. If the user is already a contact in the system, see the section "Inviting a user from a Contact Record" below.

Add New User
^^^^^^^^^^^^
If the user does not already exist or you only have the `Add New User` option, fill out the required info and click the ``Add New User`` button. To learn more about User Roles, see `Roles`_.

|newuser|

.. note:: If there is already a Contact Record in your Disciple.Tools system that represents the user you want to add, then search for that contact's name in the ``Corresponds to Contact`` box. If the user is already a contact in the system, see the section "Inviting a user from a Contact Record" below.




Inviting a user from a Contact Record
------------------------------------
If there is already a contact record for the user you want to add, there is an easy option. In the Contact Record, click the ``Dispatcher actions`` dropdown menu on the top, left. Then click ``Make a user from this contact``. Add the User's email, change the display name if needed and then click ``Create user``.

|actions|


Linking an existing contact to a user
--------------------------------------
If you realize that you have a contact that should be linked with a user account, then in the Contact Record click the ``Dispatcher actions`` dropdown menu on the top left. Then click ``Link to an existing user``.

|actions|

.. target-notes::

.. _`Roles`: https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/dt_manual/roles.html

.. |Gear| image:: /Disciple_Tools_Theme/images/Gear.png
.. |newuser| image:: /Disciple_Tools_Theme/images/Add_New_User.png
.. |existinguser| image:: /Disciple_Tools_Theme/images/Add_Existing_User.png
.. |actions| image:: /Disciple_Tools_Theme/images/Dispatcher_Actions.png
