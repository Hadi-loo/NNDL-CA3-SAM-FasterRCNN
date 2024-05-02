# NNDL CA3 - SAM & Faster RCNN

## Project Description

### Segment Anything Model (SAM)

The first part is about the implementation of the Segment Anything Model (SAM). The SAM model is a variant of the U-Net model that is used for semantic segmentation tasks. The model is trained to segment objects in images by predicting the class of each pixel in the image. We are going to use the SAM model on the [satellite images of water bodies](https://www.kaggle.com/datasets/franciscoescobar/satellite-images-of-water-bodies) dataset. The dataset contains satellite images of water bodies in different regions. Each image contains two classes: water and non-water. The goal is to train the SAM model to segment the water bodies in the images. 

### Faster R-CNN

The second part is about the implementation of the Faster R-CNN model. The Faster R-CNN model is a variant of the R-CNN model that is used for object detection tasks. The model is trained to detect objects in images by predicting the bounding box and class of each object in the image. We are going to use the Faster R-CNN model on the [Wildfire Dataset](https://drive.google.com/drive/folders/1CMqjreBO982OmtKNMKapGEzVup4W1h7b?usp=drive_link). The dataset contains images of wildfires in different regions. Each image contains multiple objects: fire, smoke, and background. The goal is to train the Faster R-CNN model to detect the fire and smoke objects in the images.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

