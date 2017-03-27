=== Photoswipe Masonry Gallery ===
Contributors: deanoakley
Author: Dean Oakley
Author URI: http://thriveweb.com.au/
Plugin URI: http://thriveweb.com.au/the-lab/photoswipe/
Tags: photoswipe, gallery, image gallery, website gallery, photoalbum, photogallery, photo, plugin, images, slideshow, short code, responsive, native gallery
Requires at least: 3.0
Tested up to: 4.6.1
Stable tag: 1.2.6

PhotoSwipe Masonry takes advantage of the built in gallery features of WordPress. The gallery is built using PhotoSwipe from Dmitry Semenov.

== Description ==

PhotoSwipe Masonry is an image gallery plugin for WordPress built using PhotoSwipe from Dmitry Semenov. [photoswipe](http://photoswipe.com/ "PhotoSwipe")
PhotoSwipe Masonry takes advantage of the built in gallery features of WordPress. Simply use the WordPress admin to create a gallery and insert it in the page.
You may need to adjust the size of the thumbnails to suit your theme in the settings.

Options are under Settings > PhotoSwipe

The PhotoSwipe Masonry gallery plugin allows you to:

* Upload multiple images at once
* Easily order images via drag and drop
* Add a title and caption

Via the options panel you can modify:

* Thumbnail size
* Full image size

Some other features include:

* Keyboard control
* Supports multiple galleries

See a [demo here](http://thriveweb.com.au/the-lab/PhotoSwipe/ "PhotoSwipeWP")

Want to contribute? See the GitHub repo (https://github.com/thriveweb/photoswipe-masonry "github.com/thriveweb/photoswipe-masonry")

== Installation ==

1. Upload `/photoSwipe-masonry/` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Upload some photos to the post or page where you want the gallery
4. Use WordPress to create a gallery and insert it in the page

== Screenshots ==

1. Screenshot Default gallery layout
2. Screenshot Popup layout

== Changelog ==

= 1.2.61 =
* Enhancement #2: now checks fig caption, title, alt and filename for image caption
* Enhancement #10: show all the images on a page in one gallery 
  (only includes images which link to an image)
* Enhancement #13: image sizes and thumbnail rebuilds unnecessary
* Enhancement #14: handle native Wordpress gallery size requested by user.
Since Wordpress image size is a maximum but gallery width is a minimum, js currently uses
Wordpress max-width/2 for the gallery thumbnail width for medium and large images to avoid undue scaling of tall portrait images.  
(Thumbnail size gallery uses thumbnail images at actual size since these are normally square in any case)

= 1.2.6 =
* Centered image fix
* History glitch fix
* Fix issue with some themes not showimg buttons on hover. Thanks Jon007.
* Fix Sharing to Facebook etc doesn't share correct image. Thanks Jon007. 

= 1.2.5 =
* Fix W3c validation issue and readme update

= 1.2.4 =
* fix for WP 4.6.1

= 1.2.3 =
* Now runs from function to simplify AJAX support

= 1.2.2 =
* Fix loading images via url in gallery mode
* Removed sharing for single images. Will try to add in future versions.
* Code tidy

= 1.2.1 =
* Fix for captions in full screen
* Tidied code

= 1.2.0 =
* Major update with support for single images in posts

= 1.1.2 =
* Removed .entry-content img { max-width: none; }

= 1.1.1 =
* masonry enqueued call causing issues. I rolled back to old style

= 1.1.0 =
* fixed alt text
* added white theme
* added caption option
* added masonry option
* fixed masonry enqueue
* added clear css
* ie9 fix

= 1.0.6 =
* gallery load from URL (#&pid=1&gid=2) fix

= 1.0.5 =
* Yoast fix

= 1.0.4 =
* css fix

= 1.0.3 =
* photoswipe dist update

= 1.0.2 =
* photoswipe dist update

= 1.0.1 =
* This is the first version
