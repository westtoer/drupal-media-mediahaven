drupal-media-mediahaven
====================

This configuration guide is based on the standard drupal installation, the current version of drupal is 7.25
For more information please visit [www.zeticon.com](http://www.zeticon.com) or contact us at [info@zeticon.com](mailto:info@zeticon.com)

Required Modules
---------------------
Upload the following required modules into the folder "sites/all/modules", some modules require additional modules to operate!
*   Media
*   File_entity
*   Views
*   Ctools
*   Styles
*   Plupload
	
Go to the "Modules" panel in your admin view and enable the listed modules.

Required Library
---------------------
Additionally to the module "plupload", the plupload library is required.
Download the plupload package from [www.plupload.com/download](http://www.plupload.com/download/)
Create a new folder "libraries" under "sites/all/" and upload the upload package to this folder.

Mediahaven Configuration Settings
---------------------
<h3>MediaHaven API</h3>
*MediaHaven login:* The login to be used by the module to communicate with MediaHaven.
*MediaHaven password:* The password to be used by the module to communicate with MediaHaven.
*MediaHaven url:* The MediaHaven url.
	
<h3>MediaHaven Upload settings</h3>
*Ingestspace id:* The MediaHaven ingestspace that will be used to upload files to.
*Auto publish:* When enabled files will be automatically published after processing. If disabled a user will have to manually publish them using the mediahaven media management software.
*Department id:* The default department where uploaded files will belong to. This will be used when autopublishing is enabled.

<h3>MediaHaven Thumbnail settings</h3>
*Thumbnail width:* Width of the thumbnails (in pixels), standard is 150px
*Thumbnail height:* Height of the thumbnails (in pixels), standard is 150px

These settings require a Mediahaven account, for more information please visit [www.zeticon.com](http://www.zeticon.com)

---------------------

WYSIWYG
---------------------
<h3>ckeditor</h3>
https://drupal.org/comment/6814058#comment-6814058
Media Browser

---------------------

Usage of the module
---------------------
In order to include media from Mediahaven into Drupal, go to Content and click the link "Add Media from Mediahaven".
Enter a search term and/or click any of the provided facets.
Select an by clicking on the image.
A confirmation "Succesfully added media" will be shown and the media file will be available for usage under the "Files" tab.