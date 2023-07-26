# phone-movement-detection-embedded-ML
This repository contains all the files and output of an embedded ML model which is trained using Edge Impulse and deployed on a smartphone. It detects the 4 movements (up/down, right/left, circular, and idle). The rest of the movements are considered anomalies.

 -> I will add a few basic steps to train your model in Edge Impulse.
 1. Log in to your Edge impulse account.
 2. Create your new project.
 3. In a dashboard you will find all of your NPY, JSON and tensorFlowLite files. These files are genereted automatically when you train your model.
 4. In devices section, you can add your edge device. Edge impulse supports many uCs but note that this repository will contain the model which I deployed on my smartphone via QR code.
 5. Head to data acquistion and add your test data. Its always a good practice to perform train/split on your data, it balances your data.
 6. Then you have to create an impulse by adding processing blocks and NN layers according to your need.
 7. Train your model and test it.
 8. Accuracy rate of 90% usually give good results.
    
    ENJOYYYYY!!!!!

Drop an email at -> fatimaehsan001@gmail.com incase you have any sort of queries.
To get some deep knowledge about Edge Impulse, I'd suggest this course -> https://www.coursera.org/learn/introduction-to-embedded-machine-learning
@ShawnHymel taught some great stuff in the above given course.
