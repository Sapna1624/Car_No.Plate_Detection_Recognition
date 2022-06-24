# Car_No.Plate_Detection_Recognition
OpenCV based project 

--> This project is the system of a vehicle’s number plate detection and recognition. 

--> **OBJECTIVE**

To create a fully functioning application that will detect the number plate from the image of any vehicle and recognize it to give the output as the number plate digits and alphabets.
It is used to detect the number plate of the vehicle andthen recognize the number plate, i.e. extract the text fromthe image. 
And all this will be done in a streamlit web-app. 


--> Google Colab notebook has been used to build the project and two open-source softwares are used to make the magic happen (namelyOpenCV and EasyOCR). 


--> **REQUIREMENTS**
First installation of the Python version of OpenCV (in your virtual environment) was done, and besides installing the OpenCVlibrary, thePython version of EasyOCR and imutils was installed in the workingenvironment. 
Also, matplotlib and numpy library has been used. Then a streamlit web app was created for better user interface.


--> **The steps followed while project creation were :- **
1) First of all, we installed the required packages and libraries inour
systems. 
2) Then the input car image is imported, which we want to workwith. 
3) Then filtering is done to simplify the image for easier and more accurate detection of the number plate. 
4) Also, edge detection techniques are applied and contours are foundthen masking is done and finally location of the number plate is found. 
5) After the car’s license plate is successfully detected and boundedbya rectangle, The focus will be on the license plate and working towardsextracting the numbers and text of the car plate using OCRcapabilities. 
6) To ensure the success of the OCR function, a series of image
processing steps were performed. 
7) In addition, the car’s license plate was also masked and enlarged. 
8) And then a web-app is to be created, using streamlit for a better user-interface. 


--> **USE OF SYSTEM**
This project serves as a stepping stone for larger scale (and more advanced) computer vision projects, such as bulk extraction of car's license plate text from large image quantities and applying these concepts on video files or live feed.



--->> **IMPLEMENTATION**

