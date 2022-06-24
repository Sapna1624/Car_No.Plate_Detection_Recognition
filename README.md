# Car_No.Plate_Detection_Recognition
**OpenCV based project**

--> This project is the system of a vehicle’s number plate detection and recognition. 



--> **OBJECTIVE**

To create a fully functioning application that will detect the number plate from the image of any vehicle and recognize it to give the output as the number plate digits and alphabets.
It is used to detect the number plate of the vehicle andthen recognize the number plate, i.e. extract the text fromthe image. 
And all this will be done in a streamlit web-app. 


--> Google Colab notebook has been used to build the project and two open-source softwares are used to make the magic happen (namelyOpenCV and EasyOCR). 




--> **REQUIREMENTS**

First installation of the Python version of OpenCV (in your virtual environment) was done, and besides installing the OpenCVlibrary, thePython version of EasyOCR and imutils was installed in the workingenvironment. 
Also, matplotlib and numpy library has been used. Then a streamlit web app was created for better user interface.




--> **The steps followed while project creation were** :- 

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


![Output_1](https://user-images.githubusercontent.com/82306590/175558588-681b6c74-9a0d-4842-bc67-684c086343e3.JPG)



![Output_2](https://user-images.githubusercontent.com/82306590/175558618-38a9e131-83f1-43ef-8723-1cce992541c1.JPG)



![Output_3](https://user-images.githubusercontent.com/82306590/175558632-59303ba1-d603-4488-b777-f8fbe1864fa4.JPG)



![Output_4](https://user-images.githubusercontent.com/82306590/175559459-4f70d74e-5d6b-43c4-90a8-08acab8efcd2.JPG)





![Output_5](https://user-images.githubusercontent.com/82306590/175559490-e671fbd8-7390-4ea9-ad93-1b16026b1430.JPG)




![Output_6](https://user-images.githubusercontent.com/82306590/175559503-75e3a8b0-83e5-4cc8-a167-a16c7fda3690.JPG)




![Output_7](https://user-images.githubusercontent.com/82306590/175559527-5e7b2dc9-1493-4702-a769-b3b72b7c4fd1.JPG)




![Output_8](https://user-images.githubusercontent.com/82306590/175559551-bdbeac9b-01d7-4fd5-8fbc-14b85ddd948b.JPG)





--->> **STREAMLIT WEB APPLICATION OUTPUT :-**


![UserInterface-1](https://user-images.githubusercontent.com/82306590/175559735-514699b2-eb07-40dd-8185-479d72e0871d.JPG)



![UserInterface-2](https://user-images.githubusercontent.com/82306590/175559913-0e73b1cc-722c-49bd-882e-49eec10a4a9f.JPG)



![UserInterface-3](https://user-images.githubusercontent.com/82306590/175559931-83c6661c-d4d1-4975-a247-c01fc5a6721b.JPG)



