# Introduction:-

SVGs are a scalable image format, which means they will easily scale to any size
and retain their quality without increasing their filesize.
They’re also very useful if you need to create or modify your images programmatically,
because you can change their properties through CSS and JavaScript.

# Benifits:-

* traditional “raster graphics”, where your image is defined by a grid of pixels.
With raster graphics, the detail is limited to the size of that pixel grid.
If you want to increase the size of the image (scale it), you have to increase the size of that grid. 

* With vector graphics on the other hand, there’s no grid. Instead, you have formulas for different shapes and lines. Since these are just formulas, it doesn’t matter how large or small you want them to appear–they can scale to any size you want, and it will have no effect on the quality or the size of the file.

* The fact that SVG source-code is XML has a few key benefits.
 First, it means that it is human-readable.
  If you were to open up a JPEG in a text editor, it would just look like gobbledygook.

# Drawbacks:-

* So, clearly SVGs are awesome! Time to go convert all of our images to SVG, right? Well, not quite. SVGs are great for relatively simple images, but because every single detail of the image needs to be written out as XML, they are extremely inefficient at storing complex images. If your image is supposed to be photo-realistic, or it has fine detail or texture (“grunge textures” are a great example), then SVGs are the wrong tool for the job.[grunge textures]https://unsplash.com/s/photos/grunge-texture


##### we can use our SVGs image through two ways:-
* Embedding its into our HTML code.(_But the thing is due to this our code can look dirt/complex_)
* or , we can use the HTML syntax for the embedding of the code according to our use.


# Assignment:-
[Read Josh Comeau’s A Friendly Introduction to SVG]https://www.joshwcomeau.com/svg/friendly-introduction-to-svg/

# Questions:-

* What are some situations where you wouldn’t want to use SVG?
* What are the benefits of “inlining” your SVGs? What are the drawbacks?
  
