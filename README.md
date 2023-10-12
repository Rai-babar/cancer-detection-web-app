# cancer-detection-web-app

Brain Tumor Detection and Segmentation Web Application
This web application is built using FastAPI and allows users to upload MRI images for both brain tumor detection and segmentation. The application provides two main functionalities:

Brain Tumor Detection: Users can upload an MRI image, and the application will use a machine learning model to determine whether a tumor is present in the image.
Brain Tumor Segmentation: Users can upload an MRI image, and the application will use segmentation model to identify and segment the tumor region within the image.

Getting Started
Follow these instructions to get the application up and running on your local machine.

Prerequisites
Before you begin, make sure you have the following installed:

Python 3.7 or higher
Pip (Python package manager)

Usage
Brain Tumor Detection:

Visit the application in your web browser.
Click the "Upload an MRI Image for Tumor Detection" button.
Select an MRI image file (in formats like .jpg, .jpeg, or .png).
Click the "Detect Tumor" button.
The result, whether a tumor is detected or not, will be displayed on the page.
Brain Tumor Segmentation:

Visit the application in your web browser.
Click the "Upload an MRI Image for Tumor Segmentation" button.
Select an MRI image file (in formats like .jpg, .jpeg, or .png).
Click the "Segment Tumor" button.
The segmented image with the tumor region highlighted will be displayed on the page.
Models
This application uses pre-trained machine learning models for both detection and segmentation. The models are stored in the project directory as follows:

Detection Model: BrainTumorDetection.h5
Segmentation Model: ResUNet-segModel-weights.hdf5
You can replace these models with your own trained models if needed.

Acknowledgments
This application was developed using the FastAPI framework and incorporates machine learning models for brain tumor detection and segmentation.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Authors
Rai Babar Ali
Feedback and Contributions
We welcome feedback, bug reports, and contributions. If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request on GitHub.

Thank you for using the Brain Tumor Detection and Segmentation Web Application!
