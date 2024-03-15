# OpenCV - Point Operators

## Description
An implementation of certain point operators known in Computer Vision field
by using opencv-python library.

## Purpose
The project shows the use of different Colour Spaces (ger. Farbräume) and 
Reinhard Color Transfer (i.e. blending two images to obtain a hybrid image).

The idea of Color Transfer is to adapt the basic color scheme of one image 
(here: Input) to a specific target color scheme (here: Target).

## Functional requirements
The project is divided in two parts.
More details can be found in [requirements document](./Aufgabe%205.pdf) (german only).
### Part 1 - Yoshi and Colour Spaces

![yoshi](./figures/yoshi.png)

    - From `figures` folder load yoshi.png and mask.png into your program.
    - Transfer the Yoshi image to the HSV color space.
    - For all white pixels in the mask image, modify the H-value in the Yoshi image.
    - Display the new image on the screen (note that imshow() can only 
    process BGR images correctly). The result should look like the image shown.
    - Build a slider to manually adjust the H-value to any desired values 
    and update the displayed image.

### Part 2 - Reinhard Color Transfer

![color_transfer](./figures/Screenshot%20from%202024-03-15%2011-09-09.png)
    
    - Implement the color transfer technique for the given FigSource.png and FigTarget.png

More details about the algorithm can be found in the [given document](./Aufgabe5.pdf)  (german only).
## Modules
- `requirements.txt`
- `figures` - contains images to be worked with
- `Farbräume.py` - Implements first set of tasks (Yoshi)
- `Farbübertrag.py` - Implements second set of tasks (Reinhard Color Transfer) 

## Special Thanks
The project was done under the coordination of Prof. Bjorn Frömmer of
Hochschule Darmstadt of Applied Sciences, Germany.

## Reference
- Reinhard et al, 'Color Transfer between Images', IEEE
Computer Graphics and Applications 21(5), 2001