Self Hosting
============

404 Errors on new install
-------------------------
If you installed Disciple.Tools and are getting 404 errors or /contacts or other pages try this:
Log in to wp-admin and go to Settings > Permalinks. You don't need to change anything, just click save at the bottom.

**Special Note for hosting on Windows servers:** If you receive a 404 error message when trying to preview or run DT after installing WordPress and the DT theme, check the root WordPress folder ``(e.g., C:\inetpub\wwwroot\wordpress)`` , and verify the web.config file exists.  If not, create a text file named "web.config," and include the following default code in the file:

.. code-block:: xml

    <?xml version="1.0" encoding="UTF-8"?>
        <configuration>
            <system.webServer>
                <rewrite>
                    <rules>
                        <rule name="WordPress" stopProcessing="true">
                            <match url="^(.*)$" />
                            <conditions>
                                <add input="{REQUEST_FILENAME}" matchType="IsFile" negate="true" />
                                <add input="{REQUEST_FILENAME}" matchType="IsDirectory" negate="true" />
                            </conditions>
                            <action type="Rewrite" url="index.php" appendQueryString="true" />
                        </rule>
                </rules>
            </rewrite>
        </system.webServer>
    </configuration>

For more information, please refer to https://www.smarterasp.net/support/kb/a1433/how-to-enable-wordpress-iis-rewrite-wordpress-iis-rewrite-example.aspx.


Backups
-------
You know that you need to keep your data backed up. Here are some things to keep in mind. Not all backups are equal. You need to have a backup that you can access if your website goes down or if your hosting provider accidentally deletes your account (this happens). This means that any backup that stays on the server your site is on isn't a reliable backup. You must have a secure **remote** backup of you Disciple.Tools instance. This can be with Amazon S3, Google Drive or any other secure storage location.

`UpdraftPlus <https://updraftplus.com/?afref=1012/>`_

We recommend and use UpraftPlus for our backups. The free version does not backup Disciple.Tools data, so **to use this plugin you must pay for the premium account**. See `UpdraftPlus <https://updraftplus.com/?afref=1012/>`_ for more info.

`BackWPup <https://wordpress.org/plugins/backwpup/>`_

We've also tested BackWPup: https://wordpress.org/plugins/backwpup/.
This plugin is free but more difficult to set up.
