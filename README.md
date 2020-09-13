# Saffron Flower detection and localization

The purpose of this project is to design a vision system for automatic harvesting of saffron which is currently done by humans.

I have created this dataset and have used [LabelImg](https://github.com/tzutalin/labelImg) to label the photos.

Then, I used [RetinaNet](https://github.com/fizyr/keras-retinanet) and its resnet50 pre-trained model and did transfer learning on my custom dataset. See [this article](https://www.freecodecamp.org/news/object-detection-in-colab-with-fizyr-retinanet-efed36ac4af3/).

After using this model, saffron flowers in input photo are detected and localized. Future works include using binocular vision to estimate 3D loacation of saffron flowers.
