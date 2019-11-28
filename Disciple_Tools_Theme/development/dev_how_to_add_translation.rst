How to Add a Translation
================================

Overview
-----------

Disciple.Tools is built on Wordpress and uses the Wordpress translation strategy. Extensive resources can be found on
`Wordpress.org <https://wordpress.org>`_ giving explanations and help for translators. `Wordpress Translation Resources <https://make.wordpress.org/polyglots/handbook/tools/glotpress-translate-wordpress-org/>`_

We invite you to contribute a new translation to Disciple.Tools, and it does not require writing code! You can submit
completed translations through Github or through email, and our commit team will review it and add it to the project.

Current Available Translations
----------------

Disciple.Tools is currently available in the following languages. Please note that as Disciple.Tools develops, additional translation commits will be needed.

- English
- Arabic
- French
- Spanish
- Turkish
- Mandarin

How to contribute
-------
We are using on online tool called POEditor. No downloading, changing, or uploading of files necessary. No coding skills needed either.

To get started click this link to join the Disciple.Tools translation project: https://poeditor.com/join/project/KcPvw3oaKD

Either select an existing language from the displayed list or click "Click here to suggest a new language" link to add the language you want Disciple.Tools to be translated in to.
Enter your email and name and then click "Join this project"

We will receive your request and approve your account as soon as possible. Once approved you will be free to start translating.


Your translations will become available to everyone when we push a release for the theme.



What are those wonky characters?
-------------------

You will see some strings that look like this:

:code:`Sorry, you don't have permission to view the %1$s with id %2$s.`

What do I do with the :code:`%1$s` and :code:`%2$s` and what do they mean?

These are placeholders that will be replaced with a something else.

Here this sentence in English could be :

 - Sorry, you don't have permission to view the contact with id 4344.
 - Sorry, you don't have permission to view the group with id 493.

In this case, :code:`%1$s` corresponds to "contact" or "group". :code:`%2$s` corresponds to the id of the record

This message can be displayed for a contact or a group. And we don't know before hand the ID of the record.
This lets you, the translator, make a sentence that is gramatically correct while still using placeholders.

To translate the sentence, just copy and paster the characters ( %s, %1$s, %2$s ) to into your translation.

In french this sentence would give:

:code:`Désolé, vous n'avez pas l'autorisation d'afficher le %1$s avec l'id %2$s.`
