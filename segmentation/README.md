### Acheived an accuracy of 79% on the validation dataset

Used some layers of the pretrained model of VGG16 for downsampling of the image.

### Helper Functions:

LoadImage - Loads a single image and its corresponding segmentation map


bin_image - Bin a segmentation map (Converts pixels from range (0, 255) to (0, classes))


getSegmentationArr - Convert RGB segmentation maps to categorical maps used for training our model


give_color_to_seg_img - Convert categorical arrays back to colored segmentation maps


DataGenerator - Returns data in form of batches
