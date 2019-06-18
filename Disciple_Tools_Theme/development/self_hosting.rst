Self Hosting
================================

404 Errors on new install
-------------------------
If you installed disciple tools and are getting 404 errors or /contacts or other pages try this:
Log in to wp-admin and go to Settings > Permalinks. You don't need to change anything, just click save at the bottom.

Step-by-step Guide
------------------

If you would like a step-by-step guide on one way that you can self-host your own instance of Disciple.Tools, email admin@kingdom.training.


Backups
--------
You know that you need to keep you data backed up. Here are some things to keep in mind. Not all backups are equal. You need to have a backup that you can access if you website goes down of if your hosting provider accidentally deletes your account (this happens). This means that any backup that stays on the server your site is on isn't a reliable backup. You must have a secure remote backup of you Disciple.Tools instance. This can be with amazon s3, google drive or any other secure storage location.

`UpdraftPlus <https://updraftplus.com/?afref=1012/>`_

We recommend and use UpraftPlus for our backups. The free version does not backup Disciple.Tools data, so **to use this plugin you must pay for the premium account**. See `UpdraftPlus <https://updraftplus.com/?afref=1012/>`_ for more info.

`BackWPup <https://wordpress.org/plugins/backwpup/>`_

We've also tested BackWPup: https://wordpress.org/plugins/backwpup/.
This plugin is free but more difficult to set up.
