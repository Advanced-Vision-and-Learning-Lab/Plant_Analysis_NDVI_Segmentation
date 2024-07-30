# Plant_Analysis_NDVI_Segmentation
This repository consists of NDVI based plant segmentation experiments

## Code
* 'NDVI_expt.ipynb': Original experiment to find the NDVI information from NIR and Red channels in raw plant images
* 'NDVI_Segmentation.ipynb': Experiment to generate segmentation mask by manually thresholding NDVI values of pixels
* 'NDVI_CRF_Refinement_Small_Object_Filtering.ipynb': Experiment to refine the segmentation masks by using 1) Conditional Random Fields, and 2) Filtering smaller objects
* 'NDVI_Segmentation_Qualitative_Comparison.ipynb': This notebook is useful for generating the qualitative comparison between the original segmentation algorithm in pipeline (yolo segmentation) vs NDVI based segmentation
