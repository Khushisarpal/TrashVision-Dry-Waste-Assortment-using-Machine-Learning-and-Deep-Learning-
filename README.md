# TrashVision-Dry-Waste-Assortment-using-Machine-Learning-and-Deep-Learning-
As a part of my degree requirements, I have completed a project which improves the assortment accuracy of dry waste using an integrated model of machine learning (ResNet) &amp; image processing (YOLOv8). Alongside the project, we have also conducted experiments and published a research paper. This contribution aligns with United Nations Sustainable Development Goal 9 (Industry, Innovation and Infrastructure) by advancing intelligent and automated solutions in waste management through innovative AI technologies.  By developing a novel classification model that combines YOLO and Inception-ResNet, this research aims to reduce human effort in waste sorting through automation. It also supports Goal 11 (Sustainable Cities and Communities) by promoting cleaner and smarter urban waste processing systems.

### The pipeline uses a two-stage deep learning approach:

#### Image Classification using Inception-ResNet V2, trained on the TrashNet dataset, to identify the type of waste.

#### Pixel-level Segmentation on manually annotated images to accurately detect and segment waste regions, enabling composition analysis.

Instead of relying on pre-annotated datasets like TACO, all segmentation masks were manually created to gain better control over data quality and model performance. The system is designed as a software-only solution, making it suitable for future integration with IoT devices such as Pi cameras in smart waste management systems.
# Key Features

Two-stage identification, which improves the accuracy of the overall model

Manual annotation for precise pixel-level segmentation

Outputs the percentage composition of waste materials in an image

Modular pipeline connecting classification + segmentation models

Built with Python, TensorFlow/PyTorch, OpenCV
# Practical Utility 
The TrashVision system shows great promise for implementation in IoT-enabled garbage segregation systems, especially 
in smart bins that are connected to conveyor belts. These systems allow for the simultaneous placement of several waste 
objects on the conveyor belt, usually five or six at a time. Each waste item is identified and localised by YOLOv8's real-time object detection capability, and the Inception-ResNet V2 classifier correctly classifies them into predefined classes, 
including plastic, glass, paper, metal, cardboard, and rubbish. Because of this, the system is ideal for automated trash 
segregation in municipal waste management facilities, recycling facilities, and industrial waste sorting lines. Scalable 
and sustainable waste processing infrastructure can be made possible by this IoT connection, which can also facilitate 
data logging, real-time monitoring, and intelligent decision-making.
