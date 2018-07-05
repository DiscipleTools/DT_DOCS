Disciple Tools Documentation
============================

Roles
-----

There are many different types of roles, each role is assigned upon account creation and can be changed later in the admin area. 

* **Administrator**: Users with this role can access all functionality, including the WordPress admin interface. They can invite other users, and they can modify the roles of other users.
* **DT Admin**: Manage users and DT settings. Can't manage plugins
* **Dispatcher**: Users with this role can access all the contacts on the site. A dispatcher would typically be tasked with assigning incoming contacts to the appropriate multiplier.
* **Marketer**: Users with this role can create new contacts. A marketer would normally be tasked with moderating and administrating any social media and may have the first conversation with a contact.
* **Multiplier**: Users with this role can see any contacts assigned to them, and any contacts shared with them. A multiplier would normally be tasked with making face-to-face meetings with any contacts they have been assigned to.
* **Prayer supporter**: Currently unimplemented.
* **Project supporter**: Currently unimplemented.
* **Strategist**: Currently unimplemented. A strategist is a role that allows leadership to view and think through the statistics and where the coalition is going. He/she is not necessarily receiving and routing contacts.
* **Subscriber/Registered**: A default WordPress role.

Contacts
--------

A contact is someone that you are trying to reach. When contact is first met, it is important to add them to the database. To do this use the ``Create new contact`` button found under the ``Contacts`` page. More info can be found on the Create_Contacts_Page_. On the contacts page, you will be able to search contacts based off of filters, and the default filter is your personal contacts. Other filters include all contacts and contacts shared with me. You can also create your own filters by pressing the ``Add new filter`` button. If you need to do a mass CSV import for contacts go to the Mass_CSV_Contacts_Import_.

Groups
------

A group is a collection of contacts. To create a new group click on ``Create new group``, then when the page loads, name and save it. Much like the contacts page, you can search groups based off of filters.  Also, like the contacts page, you can create filters with the ``Add new filter`` button. For information about the group page goto the Group_Page_.

Metrics
-------

The metrics tab is where you can see an overview of stats for the project.  Upon clicking the metrics tab, you will be presented with your personal statistics.  Clicking ``project`` then clicking ``overview`` from the now expanded subfolder will show the stats for the entire project.

Filters
-------

Filters are a way to search for contacts in either the contacts tab or groups in the groups tab. There are many default filters already included.
The filter options are located on the left of the page under the heading ``Filters``. If the default filters do not fit your needs, 
you can also make your own filters. More information about custom filters can be found on the Custom_Filters_ page.
Note that you can only have one filter active at a time.

.. _Create_Contacts_Page: user_create_contact.html
.. _Group_Page: user_group.html
.. _Custom_Filters: ./user_custom_filters.html
.. _Mass_CSV_Contacts_Import: user_mass_contacts_csv_import.html

.. toctree::

    Create Contact <./user_create_contact>
    Group <./user_group>
    Custom Filters <./user_custom_filters.rst>
    Mass CSV Contacts Import <./user_mass_contacts_csv_import.rst>
