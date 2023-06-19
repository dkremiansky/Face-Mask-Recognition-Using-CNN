# Face-Mask-Recognition-Using-CNN

We have 24345 pictures of faces at our disposal. A single person appears in (almost) every picture, with or without a face mask. The pictures depicting faces of various ages, genders, races, lighting, camera angles and types of masks. The images are colored (RGB)
And most of them are square, of different sizes. The image files are divided into two: train.tar and test.tar with 18259 and 6086
Photos respectively.

The file name of each image is of the following form: XXXXXX_Y.jpg
Where XXXXX is the unique numeric identifier of the image, and Y is the label of the image - 0 for "the person
In the picture he is not wearing a mask in a standard way" and 1- for "the person in the picture is wearing a mask in a standard way".

In this project I constructed a binary classifier so that, given an image of a person's face, it decides whether the person is in the picture Wearing a mask in a standard way or not.
