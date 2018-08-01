About
=====

Roles
-----

In Disciple Tools there are many different types of roles. Each role is assigned upon account creation and can be changed later in the admin area. 

* **Administrator**: Users with this role can access all functionality, including the WordPress admin interface. They can invite other users and they can modify the roles of other users.
* **DT Admin**: Users with this roll can manage users and Disciple Tools settings. DT Admins can't manage plugins.
* **Dispatcher**: Users with this role can access all the contacts on the site. A dispatcher is typically tasked with assigning incoming contacts to the appropriate multiplier.
* **Marketer**: Users with this role can create new contacts. A marketer is normally tasked with moderating and administrating any social media and may have the first conversation with a contact.
* **Multiplier**: Users with this role can see any contacts assigned to them as well as any contacts shared with them. A multiplier is normally tasked with making face-to-face meetings with any contacts they have been assigned to.
* **Prayer supporter**: Currently unimplemented.
* **Project supporter**: Currently unimplemented.
* **Strategist**: Currently unimplemented. A strategist is a role that allows leadership to view and think through the statistics and where the coalition is going. He/she is not necessarily receiving or routing contacts.
* **Subscriber/Registered**: A default WordPress role.

Contacts
--------

A contact is someone that you are trying to reach. You can create new contacts and edit existing ones. For a step by step guide on creating new contacts, `go here <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/user_step_by_step.html#create-a-contact>`_. On the ``Contacts`` page you will be able to search contacts based off of filters. The default filter is your personal contacts. Other filters include ``All contacts`` and ``Contacts shared with me``. You can also create your own filters by pressing the |ADD-FILTER| button. If you need to do a mass CSV import for contacts, check out the step by step `here <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/user_step_by_step.html#mass-contacts-csv-import>`_.

Groups
------

A group is a collection of contacts that are meeting (e.g., a church, Bible study, etc.). You can find the groups by clicking the |GROUPS| button at the top in the navigation menu.

Details
~~~~~~~

In this area is the following set of data:

* Name - The name of the group.
* Assigned To - Who is in charge of this group (not contacts).
* Leaders - A list of the leaders of the group (contacts) .
* Address - Where does this group meet (e.g., 124 Market St or "Jon's Famous Coffee Shop").
* Start Date - The start date of when they started meeting.
* End Date - When the group stopped meeting (if applicable).
* People Groups - The people groups that are a part of this group.
* Locations - A more general idea of locations (e.g., South_City or West_Region).

You can edit any of this data by clicking the |EDIT| button located on the top right of the details panel.

Members
~~~~~~~

|MEMBERS|

This is the area where you list the contacts that are apart of the group. To add members, click on the ``Search Members`` area and click on the name or search them. To delete a contact click on the |X| next to their name.

Multiplied Groups
~~~~~~~~~~~~~~~~~

If this group has multiplied from another group, you can add that group under ``Parent Group``.

If this group has multiplied into another group, you can add that under ``Child Groups``.

Progress
~~~~~~~~

In this area, you can keep track of the overall health and progress of the group. 

**Group Type**

The first thing you should do is define what type of group it is. Do this by clicking on the ``Group Type`` drop-down. Clicking this will reveal three options.

* Pre-Group
* Group
* Church

**Health Metrics**

Here you can track the progress of a pre-group/group/church.

If the group has committed to be a church, click the ``Covenant`` button to make the dotted line circle solid.

If the group/church regularly practices any of the following elements, then click each element to add them inside the circle.

The list of elements is as follows:

* Fellowship
* Giving
* Communion
* Baptism
* Prayer
* Leaders
* Word
* Praise
* Evangelism
* Covenant

Comments/Activity
~~~~~~~~~~~~~~~~~

Here you can write comments about activity for the group. To add a comment, click in the comment box and type your comment. Then click ``Submit comment`` to submit your comment.  To link to or "at mention" someone, type @[their name]. This section also includes the history of activity, such as when the group status became active. You can filter this section either by ``All``, ``Comments``, or ``Activity``. 

Metrics
-------

The metrics tab is where you can see an overview of stats for the project.  Upon clicking the metrics tab you will be presented with your personal statistics.  If you would like to view overall stats for your project, click ``Project`` to expand the menu. Then click ``Overview`` to view an overview of stats for your project. 

Filters
-------

Filters are a way to search for contacts in either the ``Contacts`` page or groups in the ``Groups`` page. There are several default filters included by default. The filter options are located on the left of the page under the heading ``Filters``. If the default filters do not fit your needs you can create your own. More information about creating custom filters can be found `here <https://disciple-tools.readthedocs.io/en/latest/Disciple_Tools_Theme/user_step_by_step.html#adding-custom-filters>`_.

.. note:: You can only have one filter active at a time.

Assigning, Sub-Assigning, Following, and Sharing. 
-------------------------------------------------

Contacts can only be assigned to one person and that person is responsible for them. The ``sub-assigned`` field, is usually for those who go out in twos. For example, Sam could be assigned to a contact and Fred goes with him, so he is sub-assigned. Ultimately, Sam is the one responsible for the contact. You can use the |SHARE| button when you want to give someone access so they can see the contact, without giving responsibility.

.. |SHARE| image:: /Disciple_Tools_Theme/images/share.PNG
.. |ADD-FILTER| image:: /Disciple_Tools_Theme/images/add-filter.PNG
.. |FILTERS| image:: /Disciple_Tools_Theme/images/filters.PNG
.. |GROUPS| image:: /Disciple_Tools_Theme/images/groups-button.PNG
.. |EDIT| image:: /Disciple_Tools_Theme/images/edit.PNG
.. |MEMBERS| image:: /Disciple_Tools_Theme/images/members-panel.PNG
.. |X| image:: /Disciple_Tools_Theme/images/x.PNG
