## Dataset: 
Dataset is the original dataset of Yildirim. Combining Dataset and Dataset_b for Training RA-PiredEffiNET 
## Dataset_crop: 
Dataset_crop is the processed dataset. Dataset was cropped by ROIACA. Not involved in training.
## Dataset_crop_black: 
Added a black background based on Dataset_crop, the size is 224x224. Used for training Cropping_Mobilenetv2.
## Dataset_b:
Add a black background by keeping the size of the image in the original Dataset based on the Dataset_crop. Combining Dataset and Dataset_b for Training RA-PiredEffiNET.