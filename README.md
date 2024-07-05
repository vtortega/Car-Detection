# Car-Detection R-NNN

Building a CNN for detecting car in images

With it we get familiar with the boudingbox around the objects, how to read them and how to train with that information

## Data Preparation

We start by loading the dataset, which consists of images and their corresponding bounding box annotations. The annotations include the ImageID, xmin, ymin, xmax, and ymax coordinates which define the bounding box around each detected object.

<img width="476" alt="Screenshot 2024-07-05 at 01 05 16" src="https://github.com/vtortega/Car-Detection/assets/112141870/113f18bd-4d85-432b-8db4-2fe1ab53f9fe">

## Model Definition

We use a pre-trained Faster R-CNN model for our car detection task. Faster R-CNN is a popular object detection model that can be fast and efficient.

## How impactfull is it on computing

It's important for this kind of Neural Nets to be very fast and effective, low on cumpute need, if possible, as its commonly used on mobile computers without much compute or power available.

<img width="554" alt="Screenshot 2024-07-05 at 01 05 34" src="https://github.com/vtortega/Car-Detection/assets/112141870/8d378197-e7b4-4fac-9b9a-fe6411a0fb52">

## How well does it work
some examples

<img width="404" alt="Screenshot 2024-07-05 at 01 05 55" src="https://github.com/vtortega/Car-Detection/assets/112141870/abd0cd5c-9d6f-4c9c-b89d-558d980d0228">



<img width="402" alt="Screenshot 2024-07-05 at 01 05 47" src="https://github.com/vtortega/Car-Detection/assets/112141870/7b0c00a2-6ebf-423d-8720-937725808d70">


