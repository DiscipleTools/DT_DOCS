How to Add a Translation
================================

Overview
-----------

Disciple.Tools is build on Wordpress and uses the Wordpress translation strategy. Extensive resourses can be found on
`Wordpress.org <https://wordpress.org>`_ giving explainations and help for translators. `Wordpress Translation Resources <https://make.wordpress.org/polyglots/handbook/tools/glotpress-translate-wordpress-org/>`_

We invite you to contribute a new translation to Disciple.Tools and it does not require writing code! You can submit
completed translations through Github or through email, and our commit team will review it and add it to the project.

Resources You Need
-------

 1. Click on this link to start a download of the D.T translations folder (as a zip file): |location_link|.
 
 .. |location_link| raw:: html
 
   <a href="https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/DiscipleTools/disciple-tools-theme/tree/master/dt-assets/translation" target="_blank">translations folder</a>  
 2. Unzip the translation.zip file. In the folder you will find a disciple_tools.pot file and you might see an existing translation .po file for your language in this format:  {language_code}.po. How you set up poedit will depend on if you are starting with an existing .po file or creating a new one. See instructions below.
 3. Download and install `POEdit <https://poedit.net/download>`_ free translation software.

  .. image:: /Disciple_Tools_Theme/images/translation_files.png
    :align: center
    :width: 100%

  .. image:: /Disciple_Tools_Theme/images/poedit.png
    :align: center
    :width: 100%


How To Setup POEdit for a new translation
-------------------

 1. Open POEdit.
 2. Go to File and select `New from POT/PO File...`
 3. Select .pot file that you downloaded. (see section above)
 4. Once then file is loaded, you will see the original English translation on the left and space for the new translation in the column on the right.

 .. image:: /Disciple_Tools_Theme/images/poedit_screen.png
    :align: center
    :width: 100%


 .. note:: Notice the number of translation strings at the bottom bar. This tells you how many strings are to be translated and how many are left to be translated.
 
How To Setup POEdit for an existing translation
-------------------
 1. Open POEdit.
 2. Go to File and open.
 3. Select .po file that you downloaded. (see section above)
 4. Click Catalog and then Update from POT File... 
 5. Choose the disciple_tools.pot file you downloaded.
 6. Once the file is loaded, you will see the original English translation on the left and space for the new translation in the column on the right.

Submitting Finished Translation
-------

When you save your translation file, the POEdit software will create two files (.po and .mo). We need both of these files.

**Submit through Github**

 1. Take the .po and .mo files and create a .zip archive.
 2. Go to the `issues on the Disciple Tools Github project <https://github.com/DiscipleTools/disciple-tools-theme/issues>`_ (make sure you are signed into Github).
 3. Create a new issue and attach .zip file, which contains the .po and .mo, to the issue.

**Contact us through the Contact form on Disciple Tools**

 1. Go to `Disciple Tools <https://disciple.tools/#contact>`_
 2. Fill out the contact form and let us know you want to submit a translation for the project.
 3. We'll connect with you and get the files.


