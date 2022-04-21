# Suspect-Tracking-System
Go to this path and downlaod all the required library C:\Users\Lenovo\AppData\Local\Programs\Python\Python36

This repository contains code for facial recognition using openCV and python with a tkinter gui interface. If you want to test the code then run train.py file

Technology used :
-openCV (Opensource Computer Vision)
-Python
-tkinter GUI interface

Here I am working on Face recognition based Suspect Tracking System by using OpenCV(Python). One can detect thier suspect person by simply facing the camera. 

How it works :

1) When I am run train.py then one window is opened.
2) Ask for Enter Id and Enter Name. After enter name and id then we have to click on Take Images button.
3) By clicking Take Images camera of running computer is opened and it start taking image sample of person.
4) This Id and Name is stored in folder SuspectDetails and file name is SuspectDetails.csv.
5) It takes 60 images as sample and store them in folder TrainingImage.After completion it notify that images saved successfully.
6) After taking image sample we have to click Train Image button.Now it take few seconds or minute to train machine for the images.
7) Take Image button and creates a Trainner.yml file and store in TrainingImageLabel folder.
8) Now all initial setups are done.
9) By clicking on Track Image button camera is opened once again.
10)If face is recognised by system then Id and Name of person is shown on Image. Press Q(or q) for quit this window.
After quitting it suspect person details will be stored in Suspect folder as csv file with name, id, date and time and it is also available in window.

Thank You!!
Ragini Gupta
