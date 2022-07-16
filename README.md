# Sign_Language_to_text
SIGN LANGUAGE TO TEXT
CONVERT SIGN LANGUAGE (HAND SIGNALS) TO TEXT IN REAL-TIME

Introduction:
American Sign Language (ASL) is a natural language that serves as the predominant sign language. ASL possesses a set of 26 signs known as the American manual alphabet, which can be used to spell out words from the English language. The objective of this machine learning project is to classify these hand signals and map them to text in real-time.
Data:
Dataset  for Sign Language to Text conversion  is obtained from the ASL alphabet, Image Data set for  alphabets in the American sign language 
https://www.kaggle.com/datasets/grassknoted/asl-alphabet

Approach:
1. We obtain the dataset from the ASL alphabet, Image Data set for alphabets in the American sign language.
2. Dataset preprocessing/cleaning(maximizing its information content) +Data augmentation(zooming ,rotating)+ Data Visualization using Matplotlib.

3. Using the CNN approach for training the model on the above-augmented data.

4. Using OpenCV get the bounding box for hand signals in the webcam. Then we feed these boxes to the trained model for classification.
![The-26-letters-and-10-digits-of-American-Sign-Language-ASL](https://user-images.githubusercontent.com/109040839/179367985-44b0bea3-68ea-4c17-a9af-59fa56722156.png)
![Video Feed 16-07-2022 19_00_53](https://user-images.githubusercontent.com/109040839/179368001-f33c58c3-cd86-4463-bff8-a79397f3d480.png)
