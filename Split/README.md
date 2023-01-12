# SPLIT:- A Photoshop Action
=====================================================================

#### DESCRIPTION: This is a Photoshop Action for splitting an image into its separate chromatic and monochromatic components.

Also see the following.
*https://medium.com/@terence.johnson/colour-inversion-in-photoshop-13c42d98f3cf*


## INPUT REQUIREMENT
An image comprising a single _Background layer_.

## OUTPUT
An image comprised of two layers, whose composite is identical to the input image. 	
- The _Monochrome layer_ comprises a monochrome version of the image (derived from _Image/Adjustments/Black and White_). 
- The _Colour layer_ comprises the colouration applied to the monochrome layer.

In addition the original Background layer is provided.


## UTILITY 
The decomposed image allows separate processing of the monochromatic and the chromatic content of the image.

NOTE. Some filter functions (such as _Stamp_) only support two monochrome values and do not therefore lend themselves to colour shading.  If the _Background layer_ is processed such that it can only assume values (0,0,0) and (255, 255, 255), then the image representation at _VIEW/100%_ will necessarily comprise black and white only. Colour shading will only be supported if a slight blur is applied to the monochrome component, or if a blend mode such as _Linear Light_ is selected. 

## EXAMPLES

#### Before and after the application of the Action.
 
![Before and after the application of the Action.](/../main/Split/Support%20Material/Split%20Processing.jpg)

#### Decomposition of the image

![Decomposition of the image](/../main/Split/Support%20Material/Split%20Processing2.jpg)

#### A further processing example

![A Further processing example](/../main/Split/Support%20Material/Split%20Example.jpg)


