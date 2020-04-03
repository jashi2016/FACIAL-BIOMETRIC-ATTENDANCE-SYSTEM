# FACIAL-BIOMETRIC-ATTENDANCE-SYSTEM
This is an machine learing project which is useful for face recognition and an attendance system which is based on the face biometrics.

TECHNOLOGY USED:    
1.openCV    
2.Tkinter GUI   
3.cx_Freeze 

SETUP.PY    
This programm will set the operating system and intialize the operation system to work in the path or way in which we test the file 

TRAIN.PY    
when we execute this program there will be a GUI window popping up asking you enter Id and Name and showing you some options    

This is the main program which contains three functions:    
1.TakeImages    
    This function will be executed and a window with video cam will be opened which is taking your face samples and stores in the relevant file against your name and Id    
2.TrainImages   
This function will train the gathered images and makes them ready for the prediction    
3.trackimages   
This function once executed will pops up a window which contains a camera and tracks your face.Once you press q or Q the camera will capture and store the details of the person and the time when the attendance was taken will be stored in the respective CSV file.

HAARCASCADE CLASSIFIER  
It is used to recognize the face. This classifier will consider every tracked face as a 128 dimensional feature vector and will be used to recognize where it will be matched with predicted image's vector dimensionalities.
