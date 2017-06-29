# php-image-resizer-class
PHP Image Resizer Class

PHP Class to resize images on the fly mostly while coding in HTML

### Advantages

    You would make your website load faster
    You wont have to type <img width="...px", to resize and image actually knowing it still has original its file size and width the same therefore only a good html interpreter(browser) can try to minimize the image file size
    You can use it to generate image thumbnails(more for/like cache-ing)
    You can use it to compress images to have smaller size with desired width by only manioulating the quality value i.e no need to learn/open up your photo editing software
    and many advantages you could imagine....

### Usages
To use this in your project.. is as simple as you code your html..

It resizes images of format JPG and PNG only but resizes to JPG
URL Parameters

    path -- this is the path to the image you want to resize e.g image/bg-img.jpg
    width -- the width at which you want your image to be.. e.g 50.. (note: its in pixel)
    quality -- optional: this is the quality you want the image to have, it ranges from 1 - 100, the default value is 80. e.g the images of linux shooting windows i screenshot above are resize using this tools and on the right are those i set to have a 20% quality..

#### Example Usage
``` html
    <img src=path/to/this-file.php?path=path/to/image.jpg&width=300&quality=50 />

    <img src="image.php?img=image.jpg&width=250&quality=10" />
```

### FAQs

Removed...
