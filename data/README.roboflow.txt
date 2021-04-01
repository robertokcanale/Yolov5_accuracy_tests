
Tactile_Hands_Object_Detection - v3 only_image_aug
==============================

This dataset was exported via roboflow.ai on March 24, 2021 at 9:17 AM GMT

It includes 8975 images.
Palm-Thumb-Finger-ObjDet are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 6 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Random rotation of between -30 and +30 degrees
* Random shear of between -30° to +30° horizontally and -30° to +30° vertically
* Random brigthness adjustment of between -50 and +50 percent
* Random Gaussian blur of between 0 and 3 pixels


