# IR-based-Drone-Detection-
#Overview
This project focuses on developing an AI-powered system for real-time detection and classification of unmanned aerial vehicles (UAVs) in restricted airspaces using infrared (IR) imaging and deep learning. The system enhances public safety by identifying drones amidst challenging environmental conditions, such as low light or bad weather, and providing real-time alerts to security personnel.


#Features
Real-Time Detection: Detects drones, birds, and other aerial objects using YOLOv8.
High Accuracy: Achieves 99.5% accuracy in classification and detection.
Infrared Imaging: Utilizes thermal cameras for robust detection in low-light and adverse conditions.
Edge Processing: Employs Raspberry Pi for efficient on-device image processing and alert generation.
Scalable Design: Suitable for deployment in large-scale events like Maha Kumbh Mela.
Real-Time Alerts: Generates immediate alerts via GSM, Wi-Fi, or LAN to ensure rapid response.


#Tech Stack
Programming Languages: Python
Deep Learning Frameworks: YOLOv8, TensorFlow/PyTorch
Hardware: Raspberry Pi, NVIDIA Jetson Nano (optional), IR Cameras
Data Formats: ONNX (model export), YOLO dataset format
Communication Modules: GSM, Wi-Fi, LAN
Other Tools: Jupyter Notebook, Git


#System Architecture
Infrared Imaging: Captures thermal signatures of aerial objects within a 1.5 km radius.
Edge Processing: Processes IR images on Raspberry Pi using YOLOv8 for classification.
Alert System: Sends real-time notifications through integrated communication modules.
Monitoring Platform: Displays visual data and stores logs for post-incident analysis.


#Usage
Launch the system to monitor airspace in no-fly zones.
Receive real-time alerts on detected UAVs.
Use the monitoring platform for post-incident analysis and optimization.


#Future Enhancements
Deploy IR cameras on drones for extended surveillance.
Integrate cloud computing for scalability and centralized processing.
Implement AI-based trajectory prediction and multi-object tracking.
Expand to large-scale scenarios with modular scalability.

#Workflow of the project




