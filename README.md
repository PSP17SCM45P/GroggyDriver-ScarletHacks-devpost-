# GroggyDriver-ScarletHacks-devpost-
Groggy driver detection can form the basis of the system to possibly reduce the accidents related to driver’s drowsiness. 

Comands to run:
Clone download all the files. Create a new folder name classifiers and add haar-face.xml to it.
Open command pompt and change the directory to the location where these files are downloaded. Edit in GroggyDriver.py line number15 and set the path to the downloaded haar-face.xml file in your classifiers folder.
run the command
python GroggyDriver.py --shape-predictor shape_predictor_68_face_landmarks.dat --alarm alarm.wav
