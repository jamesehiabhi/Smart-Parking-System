# Smart-Parking-System
## Unlocking the Future of Smart Parking with Computer Vision for SecurePark Solutions

<img src="https://github.com/jamesehiabhi/Smart-Parking-System/blob/main/SecurePark%20Media/SmartParking_Cover.png" width="900" height="400"/> 

### ✨Introduction
In the dynamic landscape of urban mobility, parking management stands as a significant challenge. **SecurePark Solutions** is at the forefront of this transformation, utilizing OpenCV and machine learning to develop an advanced license plate detection system. This innovative approach not only optimizes parking resource allocation and reduces congestion but also enhances security and user experience, showcasing the profound impact of smart technology on modern urban infrastructure.

### ✨Smart-Parking Requirements
- Requires ```Python``` to be installed on the system with ```OpenCV``` library. ```MongoDB``` has been used for Database.
 ``` pip install opencv-python ```
- ```Pytesseract``` is needed to be installed on the system.
  ``` pip install pytesseract ```
- A **Web-cam** is needed to test the system.
- For better results, it is recommended to get a **good quality camera** with a few changes in the code, if it is desired to be implemented in a project.

### ✨The Problem: Urban Parking Chaos
Urban areas are plagued by parking inefficiencies, leading to congestion, pollution, and frustrated drivers. Traditional parking systems often rely on manual intervention, which is time-consuming and prone to errors. **SecurePark Solutions** aims to address these issues by automating license plate detection, thereby streamlining parking management and enhancing security.

### ✨The Solution: OpenCV-Powered License Plate Detection
**SecurePark's solution** leverages OpenCV, a versatile library for real-time computer vision, to detect and recognize license plates from images of parked vehicles. The system employs a pre-trained Haar Cascade classifier, specifically designed for detecting Russian license plates, to identify and extract license plate regions from images.

### ✨The Technology Behind Automated Plate Recognition
The system is built on OpenCV's image processing capabilities, leveraging a **Haar Cascade Classifier** for detecting vehicle license plates. The key steps in the process include

**1.	Image Acquisition & Preprocessing:** The system begins by converting the input image from the default BGR color space to grayscale. This step simplifies the image data, making it easier to process and analyze.
- Capturing vehicle images using cameras.
- Converting images to grayscale for improved processing speed and accuracy.

<img src="https://github.com/jamesehiabhi/Smart-Parking-System/blob/main/SecurePark%20Media/Pre_train.png" width="600" height="400"/> 

**2.	Optical Character Recognition (OCR):** The core of the system is the Haar Cascade classifier, which is trained to detect Russian license plates. The classifier scans the grayscale image at multiple scales, identifying regions that resemble license plates.
- Extracting text from detected plates using OCR (Optical Character Recognition) technology.
- Enhancing character visibility for higher accuracy.

**3.	License Plate Detection:** The classifier outputs the coordinates of detected license plates, which are then used to draw bounding boxes around the plates in the original image. This step ensures that the detected plates are visually highlighted for further processing.
- Utilizing OpenCV's pre-trained model haarcascade_russian_plate_number.xml to locate plates within an image.
- Applying bounding boxes around detected plates.

<img src="https://github.com/jamesehiabhi/Smart-Parking-System/blob/main/SecurePark%20Media/Classifier.png" width="600" height="400"/> 

**4.	QR Code Decoding and verification:** After extracting the plate number, the system generates a QR code containing the plate information. This QR code can be used for various purposes, such as parking fee payment, vehicle identification, and access control.

<img src="https://github.com/jamesehiabhi/Smart-Parking-System/blob/main/SecurePark%20Media/QR%20Code.png" width="500" height="400"/> 

**5.	Visualization:** The final step involves displaying the processed image with the detected license plates. This allows users to verify the accuracy of the detection and take necessary actions, such as issuing parking tickets or granting access.

<img src="https://github.com/jamesehiabhi/Smart-Parking-System/blob/main/SecurePark%20Media/Visuals.png" width="600" height="400"/> 

### 🚀Technical Insights
- **Image Dimensions and Channels:** The system processes images with dimensions of 742x1200 pixels and three color channels (BGR). Converting these images to grayscale reduces the data to a single channel, simplifying the detection process.
- **Classifier Configuration:** The Haar Cascade classifier is configured with a scale factor of 1.2 and a minimum of 6 neighbors. These parameters ensure that the classifier is sensitive enough to detect license plates while minimizing false positives.
- **Bounding Box Coordinates:** The classifier outputs the coordinates of the detected license plates in the format (x, y, width, height). These coordinates are used to draw bounding boxes around the plates, making them easily identifiable.

### 🚀Key Benefits & Applications
- **Smart Parking Management:** Automates entry/exit logging and fee calculation.
- **Enhanced Security:** Prevents unauthorized access in restricted areas.
- **Law Enforcement:** Aids in stolen vehicle identification and traffic monitoring.

<img src="https://github.com/jamesehiabhi/Smart-Parking-System/blob/main/SecurePark%20Media/Multiple_cover.png" width="900" height="500"/> 

### 🚀Challenges and Considerations
While the system is highly effective, it is not without its challenges. The accuracy of the Haar Cascade classifier can be affected by factors such as lighting conditions, plate orientation, and image quality. Additionally, the system is currently trained on Russian license plates, which may limit its applicability in regions with different plate formats.

### 🚀Future Enhancements

**1.	Multi-Region Support:** Expanding the system to support license plates from various regions would enhance its versatility and global applicability.

**2.	Deep Learning Integration:** Incorporating deep learning models, such as Convolutional Neural Networks (CNNs), could improve detection accuracy and robustness.

**3.	Real-Time Processing:** Implementing real-time processing capabilities would enable the system to handle live video feeds, making it suitable for dynamic parking environments.

________________________________________
### 🚀✨Conclusion
**SecurePark Solutions** is revolutionizing urban mobility with its cutting-edge license plate detection system, showcasing the immense potential of computer vision and machine learning. This innovative solution not only enhances parking management and security but also serves as an inspiring example for young data professionals. The Smart Parking initiative further addresses urban challenges by leveraging data insights and predictive analytics, ensuring efficiency and sustainability. As AI and computer vision continue to advance, **SecurePark Solutions** remains at the forefront, driving the future of intelligent parking and urban security systems. 🚀
________________________________________

<br>

### *Kindly share your feedback and I am happy to Connect 🌟*

<img src="https://github.com/jamesehiabhi/PeterSide-HeartPredict_ML/blob/main/Displays/My%20Card1.jpg" alt="Displays" width="600" height="150"/>
