==============
Create Contact
==============

**This page is a work in progress. The code is being made to follow this documentation**

The function source code: Create_contact_function_

PHP Class function
==================

Usage
-----

`Disciple_Tools_Contacts::create_contact( $fields, true );`

Parameters 
----------

- array fields (Required):  an array of fields like name, phone number corresponding to the new contact. See [[Contact-Fields-Format]].
- check_permissions: check if the signed in user has the permission to perform this action. By default this should be true, unless this is called by an automated process.

Returns
-------

- int $contact_id, the id of the newly created contact
- WP_ERROR, in the case something went wrong.

Rest API:
---------

- url: `https://example.com/wp-json/dt/v1/contact/create`
- type: POST
- data: A JSON string of fields object. See [[Contact-Fields-Format]].
- contentType: "application/json; charset=UTF-8",
- dataType: "json",


Fields
------

Have a look at the fields page: [[Contact-Fields-Format]]


.. _Create_contact_function: https://github.com/DiscipleTools/disciple-tools-theme/blob/7ae12b653c62e995af71c15c64b65888d8e0f4d2/dt-contacts/contacts.php#L114
