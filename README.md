# syaruru-comm.github.io
website

# Manual for Modifications

## Overview
We used a website template called "OnePress" which originates in WordPress. We work on website structure and content filling/adjusting on a local WordPress interface and pack it to github pages. The property of github pages and the transferation itself allow us only a static website.

## Installment of Local WordPress Interface
Go to Bitnami (https://bitnami.com/stack/wordpress/installer) to download the installer for Windows. On Mac, you can try https://localwp.com/ (not tested work & would have different instructions). Follow the installer's instruction to complete the installment.

After the installment, you can now click on the "WordPress packaged by Bitnami Manager Tool" to start the WordPress interface. Go to "Manage Servers" and click on "Start All" to activate it.

You can now see your site on your browser at "localhost/wordpress". The editting interface is at "localhost/wordpress/login", where you will need to fill in the username and password you set in the installment. (Sometimes there would be warnings, just try to restart WordPress)

## Import the Website Files
Go to "Plugin"->"Add New", search and add "All-in-One WP Migration". Click on the newly added plugin in the left sidebar and import file from (https://drive.google.com/file/d/1stw-45imuLGv903pIyXqX-JnqzhcWyrm/view?usp=sharing) (need permission from me). If there's an update to share, export it into new files.

There's modifications over the original OnePress CSS files so that it is not a good idea to install OnePress and copy all the contents.

## Modify the Website

### Posts
The posts stand for the sections under "Projects" page. We can edit the contents in each post. On the right sidebar, the section "Featured image" is the thumbnail figure.

### Pages
The pages stand for modifications over all the sections shown in the navigation bar. Same as posts, the "Featured image" is the background image of the title of each page.

### Add New Sections
Go to "Appearance"->"Menus" to add pages to the navigation bar.

### Customize the Front Page
Go to "Appearance"->"Customize" to modify the contents on the front page. The group name part is under "Section: Hero"; The about us part is under "Section: About"->"Section Settings"; The news part is under "Section: Services"->"Section Settings"; The group member part is under "Section: Gallery"->"Section Settings". All paragraphs follow html, or can be arranged in visual mode.

### Other Style Changes
You will need to go to the original "style.css" file to edit.

## Update the Website on Github
Search and download a plugin called Simply Static. Generate static file and upload all contents to the github repository. Wait for around 5 minutes for github to update the site.
