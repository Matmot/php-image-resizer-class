# php-image-resizer-class
 

 
PHP Image Resizer Class - File

 

PHP Class to resize images on the fly mostly while coding in HTML

This Image Resizer class is a part of my project on www.dpedit.tk I tot to share this, thinking it would be useful, doh its just a simple version of the actual one i use in my picture editor project but simple enough to do the work, and for the brave developers out there you can use this script to resize images as it is uploaded to a particular size you require of your users, also can be used to create thumbnail images..


This idea is something facebook as implemented... example is a situation where by you would have to click on view full size while checking your friends profile picture before you can actually see that her/his phone's camera is superb..


Advantages

    You would make your website load faster
    You wont have to type <img width="...px", to resize and image actually knowing it still has original its file size and width the same therefore only a good html interpreter(browser) can try to minimize the image file size
    You can use it to generate image thumbnails(more like cache-ing)
    You can use it to compress images to have smaller size with desired width by only manioulating the quality value i.e no need to learn/open up your photo editing software
    and many advantages you could imagine....

Usages

 To use this tools/file/tech/idea in your project.. is as simple as you code your html..

It resizes images of format JPG and PNG only but resizes to JPG
URL Parameters

    path -- this is the path to the image you want to resize e.g image/bg-img.jpg
    width -- the width at which you want your image to be.. e.g 50.. (note: its in pixel)
    quality -- optional: this is the quality you want the image to have, it ranges from 1 - 100, the default value is 80. e.g the images of linux shooting windows i screenshot above are resize using this tools and on the right are those i set to have a 20% quality..

Example Usage

    <img src=path/to/this-file.php?path=path/to/image.jpg&width=300&quality=50 />

    <img src="image.php?img=image.jpg&width=250&quality=10" />

FAQs

 I was ask if this does open a site to any kind of vulnurability..

The answer is actually noo.. simple reasons been that - its just there in a directory, it does not connect to a database so its SQLI free, it does not take file input so you are shell scripting free, even if someone tries to manipulate the url - it would rather generate and error saying image can not be displayed or corrupt image..

Take a step to using it and i am sure you pretty much like it..
