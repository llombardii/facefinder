# Face Detection 

This program is developed in **Juypter Notebook**, using two different algorithms; **Haar Cascade** and **Deep Neural Network**. Both of the programs have the feature to capture the faces upon clicking the button 'X' on the keyboard. The clicked picture will be saved as a PNG file in the program folder.

<img width="705" alt="Screenshot 2024-02-17 at 21 34 53" src="https://github.com/llombardii/facefinder/assets/98316532/954cd5cf-9611-455b-bb78-c38b2fd0100a">

The image above is taken from upon clicking the button 'X'. This one is a product of the **Haar Cascade Classifier** algorithm. The Haar Cascade algorithm has its limitations as it is sensitive to angles.

<img width="561" alt="Screenshot 2024-02-17 at 21 23 17" src="https://github.com/llombardii/facefinder/assets/98316532/494d05b0-b018-4ff0-81f3-8cc0dec1fcfe">

This is the sample of detection using the DNN algorithm. The DNN algorithm is more efficient compared to Haar Cascade as it can detect faces at any angle or size.

Haar Cascade Classifier: https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html

YOLO Deep Neural Network: https://docs.opencv.org/4.x/da/d9d/tutorial_dnn_yolo.html
