#Face_recognition_based_attendance_system
A python GUI integrated attendance system using face recognition to take attendance.

In this python project, I have made an attendance system which takes attendance by using face recognition technique. I have also intergrated it with GUI (Graphical user interface) so it can be easy to use by anyone. GUI for this project is also made on python using tkinter.

TECHNOLOGY USED:
1) tkinter for whole GUI
2) OpenCV for taking images and face recognition (cv2.face.LBPHFaceRecognizer_create())
3) CSV, Numpy, Pandas, datetime etc. for other purposes.

FEATURES:
1) Easy to use with interactive GUI support.
2) Password protection for new person registration.
3) Creates/Updates CSV file for deatils of students on registration.
4) Creates a new CSV file everyday for attendance and marks attendance with proper date and time.
5) Displays live attendance updates for the day on the main screen in tabular format with Id, name, date and time.

# Working 
If you don't have required laibreries then firat you need to install that.

OpenCV
>pip install OpenCV-python

Numpy
>pip install numpy

Pandas
>pip install pandas

Os 
>pip install os

Tkinter 
>pip install tkinter

Now For run this project you need 'haarcascade_frontalface_default.xml' along with this python file which contains the haar cascade features of a face.
Now you are good to go.  

when you run this project you will see the simple GUI of this attendance system.were user can easily intract with this system.
First user have to register new students for that they have to enter student name and ID no. and they have to take 100 images of that student. That images will store into one perticuler folder and at the time of train our recognizer that images will be userd.When you save that profile recognizer will train and it will genrate one trainer.yml file which is used at the time of taking attendance. Now when user wants to take attendance they have to click Take attendance button and it will start webcam. A person who are standing in front of webcam if he recognize succesfuly than it will show you a name of person other wise it will show the 'Unknown' at the bottom rectengle which was displayed for face detection.

If person will detected succesfully then it will save attendance in one CSV file and it will save that CSV file into one perticuler folder.This Auto genratation of CSV file is date wise which means it will save the attendance of one day in one CSV file.  


#login_panel
![Screenshot (88)](https://user-images.githubusercontent.com/91407206/216689490-d0541aaa-10c5-4526-8bcb-d41c16b7bd81.png)


#images_captured_for_database
![Screenshot (100)](https://user-images.githubusercontent.com/91407206/216690729-aebed477-c9c5-40e1-931b-0bed4e996a86.png)


#attendance_marked
![Screenshot (101)](https://user-images.githubusercontent.com/91407206/216690751-ab661b7d-4012-4a72-a233-8b809fa90ceb.png)
