# Face-Recognition-Based-Attendance-System-Using-OpenCV
Maintaining the attendance record during online sessions is a big challenge. The conventional method of calling out roll number of each student and marking their attendance is a time-consuming task and there is always a chanced of proxy attendance. With the advent of the era of big data in the world and the commercial value of face recognition technology, the prospects for face recognition technology are very bright and have great market demand. This project aims to design a face recognition attendance system based on real-time video processing. Experimental data shows that compared with the traditional check-in method, the rate of skipping classes has greatly reduced the phenomenon of students leaving early and skipping classes in the face recognition attendance system. The face recognition attendance system with real-time video processing can quickly complete the lecturer’s tasks of attendance marking, get rid of the complex naming phenomenon, greatly improve the efficiency of class, and play an important role in guiding the development of the time and attendance system.

PROPOSED SYSTEM:
The proposed system is an application which can capture the attendance in a virtual meeting using facial recognition. It can detect and recognize the faces of the attendees. In the proposed system, at the time of enrolment, images of students are stored and recorded in a database. In real time, video of a student present in the session will be captured. The face will then be detected and matched with the dataset images, enroll number of the present student will be displayed along with updating the attendance. The proposed system has many advantages over the existing systems like it can detect faces of multiple students at a time. It saves the time and effort of the host to a greater extent. There is less chance for proxy attendance through this system as it is based on real time face recognition.

PROPOSED METHODOLOGY:
![image](https://github.com/Snig17/Face-Recognition-Based-Attendance-System-Using-OpenCV/assets/127118518/292aec05-4124-4d5e-8d67-d22ac7674427)

WORKING STEPS:

1. Data Collection:
•	Gather a dataset of face images from individuals who will be enrolled in the attendance system.
•	Ensure that the dataset includes a diverse range of images captured under different lighting conditions, angles, and expressions.
•	Annotate the dataset with labels indicating the identity of each individual.

2. Preprocessing:
•	Apply necessary preprocessing techniques such as resizing, normalization, and face alignment to ensure consistent image quality and facial alignment across the dataset.
•	Extract relevant facial features using techniques like landmark detection or deep learning-based face feature extraction models (e.g., FaceNet, VGGFace).

3. Model Training:
•	Train the model on the preprocessed dataset, optimizing it to minimize the distance between embeddings of the same person's face and maximize the distance between embeddings of different individuals.
•	Fine-tune the model if necessary to improve performance on the specific task of attendance recognition.

4. Face Detection:
•	Employ a face detection algorithm (e.g., Haar cascades, HOG, or deep learning-based face detectors like MTCNN or SSD) to detect faces in real-time or input images.
•	Ensure the face detection algorithm is capable of accurately localizing faces under various conditions.

5. Face Recognition and Attendance Tracking:
•	Once a face is detected, pass the face image through the trained face recognition model to obtain its corresponding embedding or feature vector.
•	Compare the extracted embedding with the embeddings of the enrolled individuals stored in a database.
•	Apply a suitable similarity metric (e.g., Euclidean distance or cosine similarity) to determine the closest match.
•	If a match is found above a predefined threshold, mark the attendance for the recognized individual.

6. Attendance Management:
•	Maintain a database to store the enrolled individuals' identities, corresponding embeddings, and attendance records.
•	Update the attendance records in real-time based on the recognized faces.
•	Generate reports or export attendance data as required.

7. System Evaluation and Improvement:
•	Continuously evaluate the system's performance, measuring accuracy, precision, recall, and other relevant metrics.
•	Collect feedback from users and make necessary improvements to address any identified issues or limitations.
•	Consider using techniques like data augmentation, model ensemble, or transfer learning to further enhance the system's performance.


8. Deployment:
•	Integrate the face recognition-based attendance system into the desired environment, such as classrooms, workplaces, or access control systems.
•	Ensure appropriate hardware setup, such as cameras or video feeds, to capture face images for recognition.
•	Test the system thoroughly in the deployment environment to validate its functionality and reliability.


Implementation
Main Screen:

![image](https://github.com/Snig17/Face-Recognition-Based-Attendance-System-Using-OpenCV/assets/127118518/392f95fb-cdf4-472b-8810-9545c21719cb)


Step-1: Enter Username & ID

![image](https://github.com/Snig17/Face-Recognition-Based-Attendance-System-Using-OpenCV/assets/127118518/6616a9c1-e764-473b-9f31-8e918566ce12)

Step-2: Faces Captured in Static Folder

![image](https://github.com/Snig17/Face-Recognition-Based-Attendance-System-Using-OpenCV/assets/127118518/ec8febeb-ad3f-4a09-93af-c10b1b7937f5)

Step-3: Taking Attendance

![image](https://github.com/Snig17/Face-Recognition-Based-Attendance-System-Using-OpenCV/assets/127118518/c946e993-ba76-4b74-ba1e-b830594eba31)

Step-4: Showing Attendance taken:

![image](https://github.com/Snig17/Face-Recognition-Based-Attendance-System-Using-OpenCV/assets/127118518/5b478f6b-a7cc-40c9-8975-73cfdd18ac18)

Step-5: Attendance Sheet

![image](https://github.com/Snig17/Face-Recognition-Based-Attendance-System-Using-OpenCV/assets/127118518/c947ff3b-bc58-4e41-a14e-ad0a8d61a0fe)









