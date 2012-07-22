GalleryView
===========

A simple tag plug-in for [jekyll](https://github.com/mojombo/jekyll) generating [GalleryView](http://spaceforaname.com/galleryview/) picture galleries based on a folder with pictures. Examples running this gallery plug-in can be found on [mgratzer.com](http://mgratzer.com).

#Setup 
1. Setup your site to run GalleryView photo galleries. Get the source from [github](https://github.com/jackwanders/GalleryView) and add all needed JavaScript and stylesheets to your site.

* Place galleryview_tag.rb into your jekyll **_plugins** folder.

* By default the folder **./images/gallery/** is used to find your galleries. If you want to change this value update the global variable **GALLERIES_FOLDER** at the top of galleryview_tag.rb.

* Now you can place several folders to the GALLERIES_FOLDER of your site. Each folder represents a single gallery and should only contain images. Place **{% gallery_view FOLDER_NAME %}** in your site to display all images from GALLERIES_FOLDER/FOLDER_NAME.

* GalleryView has a variety of [options](http://spaceforaname.com/galleryview/). Change them in **conifg()**. At the moment these settings are globally used for each gallery.

#License
MIT. See LICENSE.txt for details.