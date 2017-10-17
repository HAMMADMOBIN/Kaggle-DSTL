# Kaggle-DSTL
Kaggle Competition - DSTL Satellite Imagery Feature Detection

**Tools**: 

Python + Keras with TensorFlow backend 

OpenCV / Rasterio / Shapely for polygon manipulation.

**Ideas**:

1) XGBoost: pixel-based model

2) Unsupervised learning for waterway class: Canopy chloropyll content index (CCCI)

3) U-net for image segmentation:

* Assembling with different input patch size

* Cropping the output size guided by prediction loss

* Incroporating evaluation metric into the loss function

* Approximating Jaccard index such that it is differentiable

* Mirror padding for global boundaries

* Adding augmentation with rotation and reflection

* Oversampling on rare classes (sliding steps)

* Post-processing on standing water versus waterways, and small versus large vehicles.






