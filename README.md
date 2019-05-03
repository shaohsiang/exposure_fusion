# Exposure Fusion

## Introduction
<p style="text-align: justify">
Exposure fusion is a technique that creates a single image with optimal detail from a set of multi-exposed images. As developed by Tom Mertens et al., the proposed algorithm computes relevant quality measures; Contrast, Saturation, and Well-Exposedness. These measures are then combined to create a weight map used to blend each of the multi-exposed images to a single image with best exposure. </p>

## Description
Image stack: here, the multi-exposed images are combined into a stack of images to be processed
Quality measures: here, the (a) contrast, (b) saturation, and (c) well-exposedness are computed
Scalar Weight Map: here, the quality measures for Image[i] are combined and normalized
Blending: the weight maps and images are blended to obtain a final image
Final Image: this is the final image with best detail using Multiresolution blending (Multires.) 
![](exposure_fusion_image.png)  
The image below shows the image stack, decomposed quality measures, and final weight maps.  
![](steps_image.png)  


## Results
The images below shows outputs for different exposure-bracketed images.  
![](Final_HDR_image_own.png)  
![](results_1.png)  
![](results_2.png)  
![](results_3.png)  

A comparison with other methods.  
![](different_results.png)



