Users
=====

Disciple.Tools is a collaborative software that can be modified and updated by multiple users at once. Each user has his or her own login and password. Each user is assigned a particular role allowing varying degrees of access to the Disciple.Tools site. To learn more about User Roles, see `Roles`_.

The only way a user can be added to Disciple.Tools is if the site DT admin role invites him or her.

Inviting Users
--------------
Here is how a DT admin invites someone to be a user within Disciple.Tools:

1. In your Disciple.Tools site, click on the |Gear| in the top right of the page, then click ``Admin``. This will open the wp-admin page (backend of the site).

2. Click the ``Users`` tab on the left. Next, click the ``Add New`` button. 

.. note:: If you have a multisite you will have two options, ``Add Existing User`` and ``Add New User`` . If you have a single site you will only have one option, ``Add New User`` .

Add Existing User
^^^^^^^^^^^^^^^^^

You will only see this option if you are within a multisite. An existing user is someone who is already a user on another Disciple.Tools site hosted within the larger multisite server. 

More simply, a multisite is like a neighborhood of houses that share the same road network. Each house has its own address and its own key. Adding an existing user is like giving your trusted neighbor a key to your house. He/she can login to both sites and receive contacts. 

**An Example of an Exisiting User** 

If your organization has a Disciple.Tools multisite with multiple Disciple.Tools sites (for each team) within it, then you can add a user from one of these other team sites. If there was a worker on a separate team who also works closely with your team, this worker is already a user within the organization's Disciple.Tools multisite. You would have to add him/her using their already exisiting user information.

**1. Email**

If you want to add an existing user from another site, enter the user's email.

**2. Role**

The default role is "Registered." You will need to change the role according to the level of access you want to give the user. To learn more about User Roles, see `Roles`_.


**3. Corresponds to Contact**

Ignore the ``Corresponds to Contact`` unless the user you are adding corresponds to a pre-existing contact record. 

For example, if you follow-up with a seeker online, the system (e.g. Facebook plugin) will have made them a contact record in Disciple.Tools. Only the Admin and Dispatcher roles can see his record as well as the Multiplier assigned to him. Later, you want to train him in how to use Disciple.Tools so he can take new media contacts himself. The DT admin (not the Multiplier) would invite him as a user but attach this user to his already exisiting contact record. Only the DT admin would see this connection.

If you want to do this, see the section "Inviting a user from a Contact Record" below.


**4. Click ``Add Existing User`` button**

To succesfully add the exisiting user, click the ``Add Existing User`` red button. 

The user will then receive an activation email with a link. After the user clicks this link, they will be added to the Disciple.Tools site. The user will login to all sites within the multisite network using the same username/email and password.


Here is what adding an existing user looks like: 

|existinguser|



Add New User
^^^^^^^^^^^^

A new user is someone you want to give access to use your Disciple.Tools site. 

**An Example of a New User:**

If you want your teammates to start using Disciple.Tools then you will need to add each of them as new users.

**1. Username**

Create a username for the new user. They can use this username for logging into their Disciple.Tools account. A username can only be numbers and lowercase letters. It also cannot be changed in the future.


**2. Email**

Enter the user's email. They can use this email for logging into their Disciple.Tools account. An email can be changed in the future.


**3. First Name** (Only on single sites)

Enter the first name or initial of the new user.


**4. Last Name** (Only on single sites)

Enter the last name or initial of the new user.


**5. Website** (Only on single sites)

If you want to add a user's personal website, you can add it here. Otherwise this is a default Wordpress option that you can ignore.


**6. Password** (Only on single sites)

There will be automatically generated password for this new user. As the admin, you can click "Show" to view it. The DT admin as the ability to change passwords for other users, so only trusted people should have this role.

**7. Send User Notification** (Only on single sites)

Make sure this is checked in order to send the new user his/her information about their new Disciple.Tools account.


**8. Role**

The default role is "Registered." You will need to change the role according to the level of access you want to give the user. To learn more about User Roles, see `Roles`_.


**9. Corresponds to Contact**

Ignore the ``Corresponds to Contact`` unless the user you are adding corresponds to a pre-existing contact record. 

For example, if you follow-up with a seeker online, the system (e.g. Facebook plugin) will have made them a contact record in Disicple.Tools. Only the Admin and Dispatcher roles can see his record as well as the Multiplier assigned to him. Later, you want to train him in how to use Discple.Tools so he can take new media contacts himself. The DT admin (not the Multiplier) would invite him as a user but attach this user to his already exisiting contact record. Only the DT admin would see this connection.

If you want to do this, see the section "Inviting a user from a Contact Record" below.


**10. Click `Add Add User` button**

To succesfully add the new user, click the 'Add New User' red button. 

The user will then receive an activation email with a link. After the user clicks this link, they will be routed to a page with their username and password. They will also be emailed this information. It is important that they save this information in a secure location and give no one access to it. 

The user will then be able to login to your Disciple.Tools site with their username/email and password.


Here is what adding a new user looks like on a multisite: 

|newuser|



Inviting a user from a Contact Record
------------------------------------
If there is already a contact record for the user you want to add, there is an easy option. In the Contact Record, click the ``Dispatcher actions`` dropdown menu on the top, left. Then click ``Make a user from this contact``. Add the User's email, change the display name if needed and then click ``Create user``.

|actions|

.. note:: Example: If you follow-up with a seeker online, the system (e.g. Facebook plugin) will have made them a contact record in Disciple.Tools. Only the Admin and Dispatcher roles can see his record as well as the Multiplier assigned to him. Later, you want to train him in how to use Disciple.Tools so he can take new media contacts himself. The DT admin (not the Multiplier) would invite him as a user but attach this user to his already exisiting contact record. Only the DT admin would see this connection.


Linking an existing contact to a user
--------------------------------------
If you realize that you have a contact that should be linked with a user account, then in the Contact Record click the ``Dispatcher actions`` dropdown menu on the top left. Then click ``Link to an existing user``.

|actions|

.. target-notes::

.. _`Roles`: https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/getting_started/roles.html

.. |Gear| image:: /Disciple_Tools_Theme/images/Gear.png
.. |newuser| image:: /Disciple_Tools_Theme/images/Add_New_User.png
.. |existinguser| image:: /Disciple_Tools_Theme/images/Add_Existing_User.png
.. |actions| image:: /Disciple_Tools_Theme/images/Dispatcher_Actions.png
