**Face Mask Detection**

This project is a Face Mask Detection system that uses deep learning to analyze whether a person is wearing a mask or not. It is trained on a dataset containing images of faces with masks and without masks. The model can be used for real-time monitoring, safety compliance, and automated mask detection applications.

**Features**

Detects faces with masks and without masks.

Can be used on images or live video streams.

Helps enforce mask-wearing policies in public areas.

**Dataset**

The model is trained on a labeled dataset containing two categories:

With Mask – images of people wearing masks correctly.

Without Mask – images of people without masks.

**Approach**

Data Preprocessing:

Resize images to a consistent size.

Normalize pixel values.

Apply augmentation (optional) to improve generalization.

**Model Training:**

Used a convolutional neural network (CNN) to extract facial features.

The network is trained to classify faces as masked or unmasked.

Optimized using a suitable loss function and optimizer for binary classification.

Evaluation:

The model's accuracy is measured on a validation set.

Confusion matrix and performance metrics help verify detection quality.

**Usage**

Load the trained model.

Feed an image or video stream to the model.

The model outputs “Mask” or “No Mask” along with confidence scores.

Can be integrated with real-time camera feeds for live monitoring.

**Applications**

Public health monitoring in offices, schools, and public places.

Automated alerts for mask compliance.

Safety systems in hospitals, airports, and transportation hubs.
