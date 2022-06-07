# SPLIT:- A Photoshop Action
=====================================================================

#### DESCRIPTION: This is a Photoshop Action for splitting an image into its separate chromatic and monochromatic components.

## INPUT REQUIREMENT
An image comprising a single _Background layer_.

## OUTPUT
An image comprised of two layers, whose composite is identical to the input image.
	.. The _Background layer_ comprises a monochrome version of the image (derived from _Image/Adjustments/Black and White_).
      .. The _Background copy layer_ comprises the colouration applied to the monochrome layer.

## UTILITY 
The decomposed image allows separate processing of the monochromatic and the chromatic content of the image.

NOTE. Some filter functions (such as _Stamp_) only support two monochrome values and do not therefore lend themselves to colour shading.  If the _Background layer_ is processed such that it can only assume values (0,0,0) and (255, 255, 255), then the image representation at _VIEW/100%_ will necessarily comprise black and white only. Colour shading will only be supported if a slight blur is applied to the monochrome component. 

## EXAMPLES 
![](/../main/Split/Support%20Material/Split%20Processing.jpg)
![](/../main/Split/Support%20Material/Split%20Processing2.jpg)
![](/../main/Split/Support%20Material/Split%20Example.jpg)


