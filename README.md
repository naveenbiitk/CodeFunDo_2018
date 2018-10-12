# CodeFunDo_2018 

Idea: 

Forest fires cost India ₹1100 crore a year [reference](https://www.livemint.com/Politics/3tVM9yC5hRl7kapC2CNgKL/Forest-fires-cost-India-1100-crore-a-year-report.html)

Not only forest fires but also industrial fires, domestic fires etc. cause large problems to us.

Our idea is to alert people about the fire incidents before they spread rapidly and cause widespread damage.
 
We intend to create a program using Image Processing which can detect fire and alert the concerned authorities.
A low-cost monitoring camera or webcam is sufficient to demonstrate the process.

 
 Creativity: 
 
 1.We will detect fire and send its image to the email id's of concerned people.
 
 2.We also plan to create a mobile app , so that if internet connection is not available, we can alert people through phone calls or sms.
 
 3.As this method can sometimes fail by detecting false fire or similar objects , so as a major improvement in our program, we will use deep learning image classification techniques to analyse the right fire images. We also plan to extend our idea by detecting the number of people stuck at the site of accident.
 
 
 Technical details:
 
1. Image Processing: We will code in python language, and we will use the OpenCV library to process the image received from the camera and detect the image containing fire incidents.

2. If fire is detected in the image then we will use Machine learning libraries like (Scikit-learn) to detect whether it is false fire or real fire incident based on image classification on already trained data sets.
We also plan to do people detection through this library.

3. If we get the result as real fire, then we will send this image to the email id's with alert notification for manual confirmation. This programming is done using python socket's library for network connection.

4. We plan to improve this idea by creating an android app connected with a laptop, if internet connection is not available, then app will send alert notification via calls/sms.
 

