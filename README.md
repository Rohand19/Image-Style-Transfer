
# Image Style Transfer

# Table of Contents

Introduction

Step 1 — Libraries

Step 2 — Functions

Step 3 — Original and Style Images

Step 4 — Arbitrary Image Stylization

Final Step — Exporting the Result


# Introduction
We were able to achieve quicker execution times by leveraging Intel's Oneapi devcloud platform to construct this project. Oneapi's OneDNN toolkit was utilised in the creation of this project (Deep Neural Network)

# Libraries
We need to install a few libraries before anything else for this project. These libraries include Matplotlib, Numpy, TensorFlow, TensorFlow Hub, and PIL.

# Functions
### Load Image
We are decoding the image into three separate channels in this function. This is like delving into the pixel level of things. The centre of the photos are then cropped. Finally, we are resizing the image to make it the same size as our content and style photos.

### Visualize Image
As implied by the function's name, we display the plots in grid order in this function.

# Original and Style Images
This action will be simple. Selecting two pictures, we'll import them into our code. To import the photos, we'll utilise the load image function that we created earlier.

# Stylize Image
In this phase, we will define and load the TensorFlow hub model that we intend to employ. The model we'll employ is known as Arbitrary Image Styling. A model can be loaded in a variety of methods, including by downloading the model folder or by using the url.

I preferred downloading the model and importing it from my local drive for this project. The program won't need to download the model each time I run the code because of this.

[Here](https://tfhub.dev/google/magenta/arbitrary-image-stylization-v1-256/2) is the download link to arbitrary image stylization model.
(The folder was renamed to tf_model for better understanding)

# Export the stylized Image
Almost there! In this final step, we are going to visualize the final result to see the before and after of our snapshot. We will call the visualize function that we defined in the functions step.
