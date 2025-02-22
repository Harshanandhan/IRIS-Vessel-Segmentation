The Iris Vessel Segmentation project aims to identify and map blood vessels in iris images using deep learning. 
It employs a U-Net model with an EfficientNetB3 backbone to segment vessels from 544x544 images. 
The dataset, extracted from Training.zip and Testing.zip on Google Drive, contains iris images, masks, and manual annotations. Images are preprocessed with normalization and resizing, then augmented with flips and rotations. Custom functions like Dice Loss and Matthews Correlation evaluate the segmentation accuracy. 
A sliding window technique (advanced_shifted_crop) processes large images in patches, reconstructing full predictions. 
The system visualizes original images alongside predicted and ground truth masks. 
It connects to Cyber Security through biometric authentication potential. 
#Blockchain could secure the segmented data, though not implemented. Built with TensorFlow, Keras, and Python, it’s a technical exploration of AI-driven image analysis.
