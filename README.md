# AutoImagePages
Autogenerate Imagepages from a Albumpage

##What?
Use a Imagefield for multiple images for the upload and save single images as subpages

##Why?
You wanna the benefits from the usage of one page for one image, but single upload sucks....

###One Page = One Image

-additional fields (pagefields as tags, additional textfields, counterfield...) to extend the single image field
-scalability (see point above)
-great overview with the PW pagetree structure with modules like http://modules.processwire.com/modules/page-list-image-label/
http://modules.processwire.com/modules/page-list-better-label/
-like a foldergallery

##Setup

You need two templates and two fields to use this module

1. Template for the single image default name -> image
2. Template for the multiple image upload default name -> album
3. Field for the single image default name -> image
4. Field for the multiple images default name -> images

The templates could choosen from the admin module page.

##Hints

-double uploaded images (check for the imagename = filename) will be skipped
-uploaded images will saved as new childpages (template image)
-could extended with FieldtypeImageExtra to be able to edit the field entries of the images before upload/save to single images take a look at http://modules.processwire.com/modules/fieldtype-image-extra/

Thanks to Adrian Jones for realizing this little idea!
https://processwire.com/talk/user/985-adrian/
