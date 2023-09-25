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


##   Implementation

### Main Screen:

![image](https://github.com/Snig17/Face-Recognition-Based-Attendance-System-Using-OpenCV/assets/127118518/711c31f8-4732-462d-a4b6-e27e6c07f729)



### Step-1: Enter Username & ID
![image](https://github.com/Snig17/Face-Recognition-Based-Attendance-System-Using-OpenCV/assets/127118518/56713bab-752e-46c0-8eda-7ea485189326)



### Step-2: Faces Captured in Static Folder

![image](https://github.com/Snig17/Face-Recognition-Based-Attendance-System-Using-OpenCV/assets/127118518/c3efa835-3d8a-4905-86c3-6447372ea691)

### Step-3: Taking Attendance
![image](https://github.com/Snig17/Face-Recognition-Based-Attendance-System-Using-OpenCV/assets/127118518/8d6c802c-6c04-46fe-8d48-f94f2e3b7319)




### Step-4: Showing Attendance taken:
![image](https://github.com/Snig17/Face-Recognition-Based-Attendance-System-Using-OpenCV/assets/127118518/285cc82a-3612-452b-8f21-60514b82f5d0)



### Step-5: Attendance Sheet
![image](https://github.com/Snig17/Face-Recognition-Based-Attendance-System-Using-OpenCV/assets/127118518/dc6e9890-e5ad-4e6b-81bd-190386ae2dc7)










