# Image Processing and Manipulations

This project is for basic image manipulation and processing using the core scientific module NumPy. 


## Features

The program is menu-based with the following top-level features:
- Load Image
- Edit Image :
    - Horizontal Flip
    - Vertical Flip
    - Invert Colors
    - Convert to Grayscale
    - Convert to B&W
- Save Image
- Quit


## Installation


```bash
  pip install numpy
  pip install matplotlib
  pip install scikit-image
```
    
## Required Libraries

```bash
    from skimage import io, color
    from skimage.color import rgb2gray
    import matplotlib.pyplot as plt
    from skimage.util import invert
```

**NOTE:
* This Program runs for JPG Images only.
* Keep the input images and Code in the Same Folder.
