## The Concept
Traditional paper-based record keeping systems in healthcare can be time-consuming, error-prone, and can lead to delays in emergency situations. Additionally, patient identification can be a challenge, leading to medical errors and decreased quality of care. This can result in negative patient outcomes and can lead to increased healthcare costs. There is a need for a more efficient and accurate patient record keeping system that can improve patient care, reduce errors, and ultimately save lives. Meditrack proposes a smart health record keeping system that utilizes the latest facial recognition and fingerprint technology to accurately and securely identify patients, reduce the reliance on paper-based systems, and provide a more sustainable healthcare environment.

## Solution
Meditrack app proposes a smart health record keeping system that utilizes facial recognition and fingerprint technology to accurately and securely identify patients in healthcare facilities. This system eliminates the need for traditional paper-based identification methods, reducing the potential for errors and delays in emergency situations. By using cutting-edge technology, patient records can be managed more efficiently and medical staff can access critical information quickly, resulting in improved patient care and reduced healthcare costs. Additionally, this system provides an added layer of security to ensure patient information remains confidential and protected at all times. Overall, the smart health record keeping system has the potential to revolutionize patient record keeping and improve healthcare outcomes.

## What this app implements
**Main Goal**: - To develop and implement a robust Patient Identification using using AI’S Facial Recognition System and Biometrics

**Other Goals**

**Goal 1**: Develop and integrate facial recognition technology with Azure Custom AI Vision to accurately and securely identify patients.

**Goal 2**: Develop and integrate fingerprint technology ensuring uniqueness in identity with health record system.

**Goal 3**: Develop a web interface Interface for capturing or uploading facial images, display results for recognition outcomes and provides a general patient information management interface.

**Goal 4**: Implement measures to enhance the accuracy of patient identification through facial recognition and fingerprint biometrics.

## JUSTIFICATION AND SIGNIFICANCE OF THE APP

The development of a robust patient identification system using AI and biometrics is justified by several compelling factors:
**Addressing Critical Needs in Healthcare:** Current patient identification methods based on manual processes and physical IDs are prone to errors, time-consuming, and lack security. These limitations can lead to serious consequences, including medication errors, delayed treatment, duplicate medical records, and potential fraud. This project directly addresses these issues by proposing a more secure, efficient, and accurate identification system.

**Enhancing Patient Safety:** Accurate and secure patient identification is paramount for ensuring patient safety. This project seeks to minimize identification errors, which can have life-threatening consequences in healthcare settings.

**Improving Workflow and Efficiency:** Streamlining the identification process through AI and biometrics can significantly improve workflow for healthcare staff and reduce wait times for patients. This can lead to increased productivity and a better overall patient experience.

**Potential for Cost Savings:** By minimizing errors and improving efficiency, the proposed system has the potential to generate cost savings for healthcare institutions. Reduced medication errors, improved treatment protocols, and streamlined processes can contribute to overall cost reduction.

## System Architecture:

### 1.	Frontend Development (React) – THE UI INTERFACE:

•	Set up a new React project using Create React App and yarn

•	Implement the UI components based on the designed wireframes, including:

•	User authentication forms (login, registration).

•	Interface for capturing or uploading facial images.

•	Results display section for recognition outcomes.

•	Patient information management interface 

•	Utilize React Router for managing different views within the application.


### 2.	Backend Development (Node.js):

•	Initialize a new Node.js project with Express.js 

•	Implement RESTful API endpoints to handle frontend requests, including:

•	User authentication (registration, login, logout).

•	Endpoints for uploading images and sending them to Azure Custom Vision.

•	Endpoints for receiving recognition results and processing them.

•	Implement middleware for handling authentication and authorization using JWT tokens or sessions.

### 3.	Integration with Azure Custom Vision:

•	Integrate the backend with Azure Custom Vision using the Azure SDK for Node.js or Axios for HTTP requests.

•	Implement functions to send facial images to Azure Custom Vision for recognition.

•	Parse the response from Azure Custom Vision and extract relevant information for display.

### 4.	Database Setup and Connectivity (MongoDB):

•	Set up a MongoDB Atlas cluster or a local MongoDB instance.

•	Define database schemas for storing user accounts, patient information (if applicable), and session data.

•	Use Mongoose or another MongoDB ORM to interact with the database from the Node.js backend.



**Fulfilling a Gap in Existing Solutions:** While some healthcare facilities utilize basic forms of biometric identification, a comprehensive system integrating facial recognition and fingerprint verification remains relatively unexplored. This project aims to bridge this gap by creating a more robust and versatile solution.
This justification highlights the project's relevance and potential impact on the healthcare industry. By addressing critical needs, leveraging technology, and prioritizing patient safety, 

#RESULTS

1.	User authentication – Login and Registration
The register page. Here, a new patient who hasn’t been authenticated registers
![image](https://github.com/user-attachments/assets/63698fc3-9aeb-4af5-a937-53e04e1acbfc)
![image](https://github.com/user-attachments/assets/ebfaf509-6f92-41e3-ae6b-cbdba2a3fd91)
            
2.	Interface for capturing or uploading facial images.

![image](https://github.com/user-attachments/assets/4c5872d1-832b-4545-98de-f357cc879f43)
 
3.	Interface for adding patients

![image](https://github.com/user-attachments/assets/7378c612-917e-4046-8bc0-4263b426132d)

4.	Interface showing the Registered Patients

![image](https://github.com/user-attachments/assets/2f248f52-94f4-41e2-acec-badb0de7b991)


5.	Results display section for recognition outcomes

![image](https://github.com/user-attachments/assets/672f00e9-7e27-4dab-80fd-94aa2b923d14)


6.	It shows medical history.

![image](https://github.com/user-attachments/assets/6fe3eb3e-82b1-484b-93d4-31d70aa8332c)

### Objective 1: Develop and integrate facial recognition technology with Azure Custom AI Vision to accurately and securely identify patients.

It achieved 99.8% accuracy in identifying Enock Korir as one of the patients
 
![image](https://github.com/user-attachments/assets/f2d6f5c7-20e4-4091-b447-d19b3b83dc3f)

![image](https://github.com/user-attachments/assets/81830502-fe55-43c9-932f-c9503ea3937c)


Training my images for very long hours achieved a status of 100% in terms of precision, recall and AP
 
![image](https://github.com/user-attachments/assets/90902860-9167-4e00-b39a-bb33767d5adf)


### Objective 2: Develop and integrate fingerprint technology ensuring uniqueness in identity with health record system.
1.	Enrol Finger
 ![image](https://github.com/user-attachments/assets/219613e2-f1d8-4151-96c1-a363cb5b82ef)

2.	Place Finger

![image](https://github.com/user-attachments/assets/c4d4a5dc-e4f3-4ad8-a038-0d336dc89321)

 
3.	The system stores the fingers

![image](https://github.com/user-attachments/assets/5844769a-b044-4469-99f0-42fe1e6a10c8)

 
4.	The patient is registered when the id is matched with that in the database

![image](https://github.com/user-attachments/assets/6df8439f-d45a-47fa-ae8f-42ad6dbba53a)

 ### FINAL 
 
 ![image](https://github.com/user-attachments/assets/90e75d11-4db8-498c-9d72-898bed62851c)







