# Mini-Project-2
Captcha Recognition  using Deep learning and  Deployment using flask
![image](https://user-images.githubusercontent.com/70902291/123849922-037ec380-d937-11eb-95d0-e3202ad682d9.png)

1.1 INTRODUCTION
Handwritten digit recognition is the ability of a computer system to recognize the handwritten inputs like digits characters etc. from a wide variety of sources like emails, papers, images, letters etc.

In the current age of digitization, handwriting recognition plays an important role in information processing. A lot of information is available on paper, and processing of digital files is cheaper than processing traditional paper files.
 
The aim of a handwriting recognition system is to convert handwritten characters into machine readable formats. The main applications are vehicle license-plate recognition, postal letter-sorting services.

Cheque truncation system (CTS) scanning and historical document preservation in archaeology departments, old documents automation in libraries and banks, etc. 

All these areas deal with large databases and hence demand high recognition accuracy, lesser computational complexity, and consistent performance of the recognition system.

The purpose of the proposed work is to achieve comparable accuracy using a pure CNN architecture through extensive investigation of the learning parameters in CNN architecture for MNIST digit recognition. 

1.2 PROBLEM DEFINITION
To implement a classification algorithm to recognize handwritten digits (0‐ 9). This project presents our implementation of the Neural networks to recognize the handwritten numerical digits.
Deployment of the trained model as a web app using flask.

2.1 MNIST AND MATH SYMBOL DATASETS
  The MNIST dataset, a subset of a larger set NIST, is a database of 70,000 handwritten digits, divided into 60,000 training examples and 10,000 testing samples. The images in     the MNIST dataset are present in form of an array consisting of 28x28 values representing an image along with their labels. Also, we have used dataset from math symbol         
  containing 7000 samples each for ‘-’ and ‘+’, 3251 samples for ‘*’ and 868 samples for ‘/’. Merging of data resulted in 76307 samples for training and 11812 samples for         testing dataset.

3. LIBRARY USED
•	Python 3 and above 
•	TensorFlow library for training and inference of deep neural networks.
•	Keras library for interface of TensorFlow library
•	Flask framework to deploy model

4. CNN MODEL SUMMARY


![image](https://user-images.githubusercontent.com/70902291/123850360-90c21800-d937-11eb-98ec-3018e0309bda.png)









5. RESULTS
   Training  and Validation Accuracy:
   
   
   
   ![image](https://user-images.githubusercontent.com/70902291/123850473-b3543100-d937-11eb-95ef-f542893d6d0d.png)

 
   Testing Accuracy:
   

   ![image](https://user-images.githubusercontent.com/70902291/123850507-bc450280-d937-11eb-8999-c2bf8203bb42.png)


   Model Deployment using Flask Demo:
   
   
   
  ![image](https://user-images.githubusercontent.com/70902291/123850545-cb2bb500-d937-11eb-8ff9-80e3053b0469.png)




6. PROBLEMS FACED AND LESSONS LEARNT
•	Faced issue of overfitting and shuffled the dataset. 
•	Math dataset and MNIST dataset compatibility issue resolved by converting the math dataset samples to binary images.
•	Faced many issues related to Trained model deployment using Flask library, fixed the issues by referring multiple online sources and got exposure to flask functionalities.

7. REFERENCES
•	https://www.mdpi.com/1424-8220/20/12/3344/htm
•	https://core.ac.uk/download/pdf/231148505.pdf
•	https://www.freecodecamp.org/news/an-intuitive-guide-to-convolutional-neural-networks-260c2de0a050/
•	https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53
•	https://towardsdatascience.com/a-laymans-guide-to-building-your-first-image-classification-model-in-r-using-keras-b285deac6572


