# Image Optimization for Thracian Tombs Website


## File Format
The recommended file format is jpeg.


## Optimization Processes
The images are optimized with ImageMagicks `mogrify` and jpegoptim`

### Example: Size the images on a 3:2 format and resize them 
`mogrify -gravity center -crop 3:2 -resize 2400 *`

### Example: Optimize image for defined file size.
`jpegoptim --size=500k *`


## Recommended Image Resolitions and File Size

### Full Width Images
* ratio:  3:2
* width:  2400px
* height: 1600px
* size:   ~500kb

### Slideshow images
* height: 1500px
* size:   ~470kb

### Inside Content Images Horizontal
* width:  1000px
* size:   ~470kb

### Inside Content Images Vertical
* height: 1500px
* size:   ~470kb

### Blogpost Images
* width:  1500px
* size:   ~470kb
