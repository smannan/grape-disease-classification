## Repository containing experiments to classify five types of grape diseases

### Dependencies:

- python3
- tensorflow
- PIL
- Keras
- numpy

### Disease Classes

1. Healthy Leaves
2. Phylloxera
3. Leaf Blight
4. ESCA measles
5. Mildew
6. Black rot

There are 1,110 images with 200 images per class.


Images are zipped in grape-disease-data.zip and were stored on a shared Google Drive for training.


Google Colab and tensorflow were used to train the models.


### Models


Inception-Resnet-V2 with transfer learning showed ~85% validation accuracy.
