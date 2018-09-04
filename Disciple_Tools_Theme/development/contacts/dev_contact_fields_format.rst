Contact Fields Format
=====================

Fields have different types. Each type will need it's own syntax.
The list of fields will changed based on your install. For a list of available fields have a look at: [Contact Post Type page](https://github.com/DiscipleTools/disciple-tools-theme/blob/master/dt-contacts/contacts-post-type.php)

Text
----

Field examples:

* title

.. code:: php

  fields = [
    "title" => "John Doe" 
  ]


key_select
----------

Field examples:

* overall_status
* seeker_path

The options for each of these can be found in the [Contact Post Type page](https://github.com/DiscipleTools/disciple-tools-theme/blob/master/dt-contacts/contacts-post-type.php)
The key is used to set save the field instead of the value.

.. code:: php

  fields = [
     "overall_status" => "active"
  ]


multi_select
------------

Field examples:

* sources
 
.. code:: php

  $fields = [
    "sources" => [
      "values" => [ 
        [ "value" => "web" ],  //add new, or make sure it exists
        [ "value" => "phone", "delete" => true ] //remove existng
      ],
      "force_values" => false // true will set source to the values entries. removing all others
    ]
  ]

Contact Fields
--------------
* contact_phone
* contact_email
* contact_address
* contact_facebook
* etc

There are three actions you can take:
* Create, if you don't include a key, a new field will be created
* Update, include the key and value to update
* Delete, including the key and the delete flag will remove the Phone number

.. code:: php

  $fields = [
    "contact_phone" => [
      ["value" => "94 39 29 39"], //create
      ["key" => "contact_phone_123", "value" => "43 42 45 43"],  //update
      ["key" => "contact_phone_123", "delete" => true] //delete
    ] 
  ]
  
To change a detail on a contact method:

.. code:: php

  $fields = [
    "contact_phone" => [
      ["key" => "contact_phone_123", "verified" => true],  //update verified flag
    ]
  ]


Date
----

* baptism_date

.. code:: php

  $fields = [
    "baptism_date" => "2018-12-31" //format yyyy-mm-dd
  ]


user_select
-----------

* assigned_to //int, a user id

.. code:: php

  $fields = [
     "assigned_to" => 4  //the id of the user
  ]


Number
------

* quick_button_no_answer
* quick_button_phone_off
* quick_button_phone_off
* quick_button_contact_established
* quick_button_meeting_scheduled
* quick_button_meeting_complete
* quick_button_no_show

.. code:: php

  $fields = [
    "quick_button_no_answer" => 3
  ]


Connections
-----------

* locations
* groups
* people_groups
* baptized_by
* baptized 
* coaching 
* coached_by
* subassigned

Let's say our contact is connected to locations with IDs 1, 3 and 43.
This example will add the location with ID 1 and will remove the location with ID 43. The contact will then be connected to locations 1 and 3

.. code:: php

  $fields = [
    "locations" => [
      "values" => [ 
        [ "value" => 1 ],
        [ "value" => 43, "delete" => true ]
      ],
      "force_values" => false // true will set locations to the values entries. removing all others
    ]
  ]

This example will remove locations 1 and 3 and leave the contact connected to location 5:

.. code:: php

  $fields = [
    "locations" => [
      "values" => [ 
        [ "value" => 5 ],
      ],
      "force_values" => true // true will set locations to the values entries. removing all others
    ]
  ]



Fields example together
-----------------------

.. code:: php

  $fields = [
    "title" => "Bob",
    "overall_status" => "active",
    "contact_phone" => [
      ["value" => "43 42 45 43"],
      ["value" => "94 39 29 39"]
    ],
    "locations" => [ 
      "values" => [
        [ "value" => "9" ]
      ]
    ],
    "quick_button_no_answer" => 3,
    "baptism_date" => "2017-11-34",
  ]
  Disciple_Tools_Contacts::create_contact( $fields, true )

JavaScript example with REST
----------------------------

.. code:: javascript

  jQuery.ajax({
    type: "POST",
    data: JSON.stringify({
      title:"bob", 
      contact_phone:[{value:"12324"}]
    }),
    contentType: "application/json; charset=utf-8",
    dataType: "json",
    url: wpApiSettings.root + `dt/v1/contact/create`,
    beforeSend: function(xhr) {
      xhr.setRequestHeader('X-WP-Nonce', wpApiSettings.nonce);
    }                
