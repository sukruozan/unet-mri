# unet-mri
UNet Training for MRI Image Segmentation

- The code is the slight modification of [this implementation](https://blog.paperspace.com/unet-architecture-image-segmentation/)
- You can use Inputs and Labels folders to upload your own input and label images. Input images are (256,256,3) RGB jpeg images. Output labels are binary (256,256) png images.
- Label images are generated by using [this repo](https://github.com/sukruozan/level-set) which utilizes the level-set method.
- There are 10 standard and 10 augmented samples for you to try.
- You can load the pre-trained model parameters from  [this file](brainMRI_segmentation.h5)
- You can use [this jupyter notebook](BrainMRISegmentation_PreTrained.ipynb) to load trained model and perform predictions.
- You can use [this jupyter notebook](BrainMRISegmentation_Train.ipynb) to train your own model with your training input-label pairs.

