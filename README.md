ZBMP Web Sweeper & Converter
=============

This generates zbuffer-sweeping preview from ZBMP/MBMP backgrounds from Microsoft 3D Movie Maker.

[▶️ Try Converter](https://phantomcrew-de.github.io/zbmp-sweeper-converter/zbmp-converter.html) | 
[▶️ Try Sweeper](https://phantomcrew-de.github.io/zbmp-sweeper-converter/zbmp-sweeper.html)


| RGB-Ramp | Monochrome |
|--------|--------|
| ![/img/prev_image_01.png](/img/prev_image_01.png) | ![/img/prev_image_02.png](/img/prev_image_02.png) |
| ![/img/prev_image_03.png](/img/prev_image_03.png) | ![example zbmp sweep gif](http://i.imgur.com/EQBpRHX.gif) |




Requirements
============

* Python 2.7
* [numpy](http://www.numpy.org/)
* [PIL](http://www.pythonware.com/products/pil/) or [Pillow](https://pillow.readthedocs.org/en/3.0.x/installation.html)
* [3dmm Pencil++](http://frank.weindel.info/proj.pencil.html)
* [3D Movie Maker](https://en.wikipedia.org/wiki/3D_Movie_Maker)

Usage
=====
* Open BKGDS.3CN in 3dmm Pencil++. 
* Find the MBMP of the scene you want to export. 
* Click View/Edit, select the correct palette, and export to a BMP.
* Find the matching ZBMP (tree view helps here, as they'll be grouped under a single CAM)
* Click Export.. Give it a similar filename to the BMP you exported. Click "Yes" if you are asked if you want to decompress.
* Run build-sweep.py filename.bmp filename.zbmp in a console. You can run build-sweep.py --help for additional options

TODO:
=====

* Include lib3dmm & an MBMP parser so 3dmm Pencil++ isn't needed
* Configurable sweep highlight color
* Disablable sweep highlighting
* Start greyscale, and then sweep to color?

## About This Fork

This fork was created for the **3D Movie Maker Remastered Project**.
It is used for development, customization, and testing related to the remastered version of the original 3D Movie Maker.
For more information, please visit:
[Project Website](https://phantomcrew.eu/3DMM/)
