# solar-panel-fault-detection
Solar Panel Fault Detection System Using Thermal Imaging

Project Overview:
This project develops an AI-based system to automatically detect faults in solar panels using thermal images. The system classifies various fault types such as dust, bird droppings, electrical faults, physical damage, and snow cover to help maintain solar panel efficiency and reduce manual inspection time.

Key Features:

Uses thermal image data of solar panels for fault detection

Implements a convolutional neural network (CNN) with transfer learning (MobileNetV2)

Applies data augmentation to improve model accuracy

Automatically classifies faults into six categories

Provides fast and accurate fault identification to support preventive maintenance


Technologies Used:

Python programming language

TensorFlow and Keras deep learning frameworks

MobileNetV2 pre-trained CNN model for transfer learning

Jupyter Notebook for coding and experimentation

Matplotlib and Seaborn for data visualization


Dataset:

Collected and labeled thermal images of solar panels

Fault categories: Bird-drop, Clean, Dusty, Electrical damage, Physical damage, Snow-covered

Images preprocessed and resized to 224x224 pixels


How to Use?

Clone this repository

Install required Python packages: numpy, matplotlib, opencv-python, tensorflow

Run the Jupyter Notebook to train or use the pre-trained model for prediction

Use the model to classify new thermal images for fault detection


Results:

Achieved high accuracy (~100%) in fault classification

Precision, recall, and F1-scores demonstrate strong model performance across all fault categories

The system reduces manual inspection efforts and improves solar farm maintenance efficiency


Future Scope:

Expand dataset with more fault examples

Deploy system for real-time solar farm monitoring

Integrate with solar asset management platforms


Acknowledgements:
Dataset and thermal images collected during the project
MobileNetV2 model and TensorFlow open-source frameworks
