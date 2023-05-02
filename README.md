# Comparative Analysis of Image Segmentation
## Overview
Image segmentation is an important problem in computer vision that involves dividing an image into meaningful regions or objects. In this report, we provide an overview of the different techniques and algorithms used for image seg-mentation where we apply a comparative analysis of differ-ent deep learning methods. We modified the U-Net standard architecture and compared these architectures. We have also generated image labels for this segmentation process.

## Approach:
1. Using the Original U-NET Architecture: The U-NET architecture is a popular deep learning architecture for image segmentation that was introduced in 2015. It consists of a contracting path that down samples the image and a symmetric expanding path that up samples the image. The architecture uses skip connections between the contracting and expanding paths to preserve spatial information.
<p align="center">
  <img src="Output_images/SegmentationwithUNET_groundtruth_finaloutput3.png" alt="image_description" width="400"/><br>
 </p>
2. Using the DenseNet121 Model along with the U-NET architecture: DenseNet is another deep learning architecture that has shown good performance for image segmentation. In this approach, the DenseNet121 model is used as the backbone for the U-NET architecture.
<p align="center">
  <img src="Output_images/DENSENET_withUNET_finaloutput2.png" alt="image_description" width="400"/><br>
 </p><br>
4. Using the RESNET50 Model along with the U-NET architecture: This method uses the RESNET50 model as the backbone for the U-NET architecture.
5. Segmentation with K-means clustering and U-NET architecture: This approach combines the K-means clustering method with the U-NET architecture to perform image segmentation. The K-means algorithm is used to cluster the labels in the image into different regions, and then the U-NET model is trained to segment each region.
6. Segmentation with DBSCAN clustering and U-NET architecture: This approach combines the DBSCAN clustering method with the U-NET architecture to perform image segmentation. The DBSCAN algorithm is used to cluster the labels in the image into different regions, and then the U-NET model is trained to segment each region.
7. SegNET with VGG16 Architecture: SegNET is another deep learning architecture that is specifically designed for image segmentation. It consists of an encoder network that downsamples the image and a decoder network that upsamples the image. The architecture uses pooling indices from the encoder network to perform upsampling in the decoder network. In this case VGG16  is used as backbone.
8. SegNET with Mobilenet Architecture: In this architecture of Segnet, Mobilenet is used as backbone.
