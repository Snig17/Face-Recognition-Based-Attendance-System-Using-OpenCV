# Face-Recognition-Based-Attendance-System-Using-OpenCV
Maintaining the attendance record during online sessions is a big challenge. The conventional method of calling out roll number of each student and marking their attendance is a time-consuming task and there is always a chanced of proxy attendance. With the advent of the era of big data in the world and the commercial value of face recognition technology, the prospects for face recognition technology are very bright and have great market demand. This project aims to design a face recognition attendance system based on real-time video processing. Experimental data shows that compared with the traditional check-in method, the rate of skipping classes has greatly reduced the phenomenon of students leaving early and skipping classes in the face recognition attendance system. The face recognition attendance system with real-time video processing can quickly complete the lecturer’s tasks of attendance marking, get rid of the complex naming phenomenon, greatly improve the efficiency of class, and play an important role in guiding the development of the time and attendance system.

PROPOSED SYSTEM:
The proposed system is an application which can capture the attendance in a virtual meeting using facial recognition. It can detect and recognize the faces of the attendees. In the proposed system, at the time of enrolment, images of students are stored and recorded in a database. In real time, video of a student present in the session will be captured. The face will then be detected and matched with the dataset images, enroll number of the present student will be displayed along with updating the attendance. The proposed system has many advantages over the existing systems like it can detect faces of multiple students at a time. It saves the time and effort of the host to a greater extent. There is less chance for proxy attendance through this system as it is based on real time face recognition.

PROPOSED METHODOLOGY:
![image](https://github.com/Snig17/Face-Recognition-Based-Attendance-System-Using-OpenCV/assets/127118518/292aec05-4124-4d5e-8d67-d22ac7674427)

WORKING STEPS:

Step -1:We are importing the required libraries.

Step-2:Defining the Flask App.

Step-3:Functions that return today’s date strings to use in the program ahead.

Step-4:Initializing Video Capture object to access Webcam.

      Checking if the required folders are in place or not, If not create them.
      
Step-5:Define Functions
      A function that calculates the number of total registered users.
      A function that extracts the face from an image.
      A function that Identifies face using ML model.
      A function that trains the model on all the faces available in the faces folder.
      A function that extracts info from today’s attendance file in the attendance folder.
      A function that adds the Attendance of a specific user in our today’s Attendance file.
      
  Step-6 : Define main page routing function.

    This function will run when we click on Take Attendance Button.
    This function will run when we add a new user.
    Our main function which runs the Flask App.

