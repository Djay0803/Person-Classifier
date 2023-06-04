
# Person Classifier

In this project, our primary goal is to perform face matching by comparing an input image with the images already present in our model. To achieve this, we first train the model using a set of images belonging to four different individuals. The training process involves leveraging the SVM (Support Vector Machine) algorithm for classification. SVM helps us categorize the input images into the respective individuals.

To detect faces within the images, we utilize the Haarcascade Classifier, a widely used algorithm for face detection. By applying the Haarcascade Classifier, we are able to identify the facial regions in the input images, allowing us to focus on the important features during the matching process.

Once the model is trained, we save it for later use. The user interface (UI) and user experience (UX) are implemented using Flask, a web framework in Python. The backend of the application is developed using Python.

The application workflow involves uploading an image containing a person's face. If the uploaded image matches any of the images stored in the model, the application displays the percentage score indicating the level of similarity between the uploaded image and the matching image in the model.

In summary, this project combines face matching using SVM classification, face detection using the Haarcascade Classifier, and a Flask-based UI/UX for uploading and comparing images. The result is a system that can identify and provide a percentage score for the similarity between an uploaded image and the stored images in the model.


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install following packages.

```bash
pip install numpy
pip install opencv-python
pip install matplotlib
pip install Flask
```    
## Authors
- [Dhananjay Prajapati](https://www.linkedin.com/in/dhananjay-prajapati-35a1941b0)
