# BioUNet
Semantic Segmentation of Biological Images

SRS:
The architecture of the UNet model follows a fully convolutional model.
The model consists of Encoding and Decoding blocks with skip connections between the same-sized layers.

The resulting shape of the shrinking layers back into the enlarging layers resembles a 'U',
hence the name.

This architecture is particularly useful in near-pixel-perfect segmentation and will be utilized
for segmenting biomedical/biological images.
