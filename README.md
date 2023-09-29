## Face_recognition_based_attendance_system
A python GUI integrated attendance system using face recognition to take attendance.

In this python project, I have made an attendance system which takes attendance by using face recognition technique. I have also intergrated it with GUI for ease of access, tkinter is the supported format for the same.

## TECHNOLOGY USED:
1) Python
2) OpenCV, (cv2.face.LBPHFaceRecognizer_create())
3) CSV

## FEATURES:
1) Easy to use with interactive GUI support.
2) Password protection for new person registration.
3) Creates/Updates CSV file for deatils of students on registration.
4) Creates a new CSV file everyday for attendance and marks attendance with proper date and time.
5) Displays live attendance updates for the day on the main screen in tabular format with Id, name, date and time.

## Working 
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

Now to run this project you need 'haarcascade_frontalface_default.xml' along with this python file which contains the haar cascade features of a face.


When you run this project you will see simple GUI of this attendance system where user can easily intract with this system.
First user have to register new students for that they have to enter student name and ID no. and they have to take 100 images of that student. That images will be stored into one  folder and at the time of training our recognizer that images will be used. When you save, that profile recognizer will train and it will genrate one trainer.yml file which is used at the time of taking attendance. Now when user wants to take attendance they have to click 'Take Attendance' button and it will start webcam. A person who is standing in front of webcam if recognized successfully than it will show name of person otherwise it will show 'Unknown' at the bottom rectengle which was displayed for face detection.

If person get detected succesfully then it will save attendance in CSV format and will save that CSV file.  


## login_panel
![Screenshot (88)](https://user-images.githubusercontent.com/91407206/216689490-d0541aaa-10c5-4526-8bcb-d41c16b7bd81.png)


## images_captured_for_database
![Screenshot (100)](https://user-images.githubusercontent.com/91407206/216690729-aebed477-c9c5-40e1-931b-0bed4e996a86.png)


## attendance_marked
![Screenshot (101)](https://user-images.githubusercontent.com/91407206/216690751-ab661b7d-4012-4a72-a233-8b809fa90ceb.png)
