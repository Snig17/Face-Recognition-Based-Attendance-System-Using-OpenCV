# Face-Recognition-Based-Attendance-System-Using-OpenCV

## PROPOSED SYSTEM:
The proposed system is an application which can capture the attendance in a virtual meeting using facial recognition. It can detect and recognize the faces of the attendees. In the proposed system, at the time of enrolment, images of students are stored and recorded in a database. In real time, video of a student present in the session will be captured. The face will then be detected and matched with the dataset images, enroll number of the present student will be displayed along with updating the attendance. The proposed system has many advantages over the existing systems like it can detect faces of multiple students at a time. It saves the time and effort of the host to a greater extent. There is less chance for proxy attendance through this system as it is based on real time face recognition.

##  PROPOSED METHODOLOGY:


##  WORKING STEPS:

###  1. Data Collection:
   
•   	Gather a dataset of face images from individuals who will be enrolled in the attendance system.

•   	Ensure that the dataset includes a diverse range of images captured under different lighting conditions, angles, and expressions.

•   	Annotate the dataset with labels indicating the identity of each individual.

###  2. Preprocessing:
•	   Apply necessary preprocessing techniques such as resizing, normalization, and face alignment to ensure consistent image quality and facial alignment across the dataset.

•   	Extract relevant facial features using techniques like landmark detection or deep learning-based face feature extraction models (e.g., FaceNet, VGGFace).

### 3. Model Training:

•	Train the model on the preprocessed dataset, optimizing it to minimize the distance between embeddings of the same person's face and maximize the distance between embeddings of different individuals.

•	Fine-tune the model if necessary to improve performance on the specific task of attendance recognition.

### 4. Face Detection:

•	Employ a face detection algorithm (e.g., Haar cascades, HOG, or deep learning-based face detectors like MTCNN or SSD) to detect faces in real-time or input images.

•	Ensure the face detection algorithm is capable of accurately localizing faces under various conditions.

### 5. Face Recognition and Attendance Tracking:

•	Once a face is detected, pass the face image through the trained face recognition model to obtain its corresponding embedding or feature vector.

•	Compare the extracted embedding with the embeddings of the enrolled individuals stored in a database.

•	Apply a suitable similarity metric (e.g., Euclidean distance or cosine similarity) to determine the closest match.

•	If a match is found above a predefined threshold, mark the attendance for the recognized individual.

### 6. Attendance Management:

•	Maintain a database to store the enrolled individuals' identities, corresponding embeddings, and attendance records.

•	Update the attendance records in real-time based on the recognized faces.

•	Generate reports or export attendance data as required.

### 7. System Evaluation and Improvement:

•	Continuously evaluate the system's performance, measuring accuracy, precision, recall, and other relevant metrics.

•	Collect feedback from users and make necessary improvements to address any identified issues or limitations.

•	Consider using techniques like data augmentation, model ensemble, or transfer learning to further enhance the system's performance.


### 8. Deployment:

•	Integrate the face recognition-based attendance system into the desired environment, such as classrooms, workplaces, or access control systems.

•	Ensure appropriate hardware setup, such as cameras or video feeds, to capture face images for recognition.

•	Test the system thoroughly in the deployment environment to validate its functionality and reliability.


## Implementation

Main Screen:



Step-1: Enter Username & ID


Step-2: Faces Captured in Static Folder


Step-3: Taking Attendance



Step-4: Showing Attendance taken:



Step-5: Attendance Sheet









