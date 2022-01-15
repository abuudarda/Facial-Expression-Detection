Research Paper Summary:








URL: https://www.researchgate.net/publication/346554975_Emotion_Detection_using_Image_Processing_in_Python








2. Background: 
The objective of the paper is to develop a system that can analyze the image and predict the expression of a person. Emotions possessed by humans have a vast scope of study in the computer vision industry that can be helpful in further machine learning research. 

3. Summary of contributions:
Through this project, the emotional or facial expressions would be recognized which can be derived from the live feed through any image or any system’s camera. The results of this method can be extraordinary if a valid pre-existing database or a newer database is deployed in the process. Thus, the scope of advancement in the camera industry would become much higher as the AI sensors would get much more precise for the interaction between a human and a device. Moreover, the research could lead to newer papers through the application of better algorithms or other classical methodologies. 

4. Limitations and discussion:
The most significant drawback of facial recognition is the test cases can be controlled by humans and the results can be intentionally or unintentionally falsified. The limitation of the paper we used is that it cannot develop itself by calculating the errors it made. It could have used some kind of deep learning algorithm to achieve that property. Moreover, some pairs of emotions might get misclassified. For example, expressions like sadness would get confused with a neutral state, this would make the process less reliable. Hence, the limitation states performance issues with facial recognition will drain its accuracy.

5. Why this paper?:
Emotion recognition is a large area where many papers have been written. We went through many papers but chose this one because it seemed the process is well described here. We do feel like we have gained from the paper.


6. Wider research context: 
The paper presents that it is possible to recognize human emotions by only facial recognition with high accuracy. It would be helpful for the next generation of human-computer interactions where it would be possible to perceive human feedback and respond accordingly, improving the performance of current interfaces.


Project description:


In this project, a person's facial expressions will be detected using TensorFlow and Python according to their facial expressions. Emotion recognition can be used hugely in different companies or markets. A consumer’s or customer’s motive toward a product can better be gauged by analyzing his facial expression than his words. This technology offers better opportunities in market research and digital advertising. This project will be done using Python 3.8, TensorFlow, Numpy, pandas, etc. The paper chosen for this project will be used as a baseline of this project. In this paper, Emotion Recognition using human facial expressions has been done that matches the objectives of this project. The ultimate aim of this project is to improve the result of the paper.


The input of this project will be the images of human facial expressions and, the output of this project will be to detect the emotion i.e. surprise, happiness, disgust, neutral, sad, angry, fear.


The FER-2013 Dataset will be used for this project dataset consisting of 34034 labeled images in the training set, 3,589 labeled images in the development set, and 3,589 images in the test set. The dataset was created by gathering the results of a Google image search of each emotion and synonyms of the emotions. Each image in FER-2013 is labeled as one of seven emotions, such as happy, sad, angry, afraid, surprise, disgust, and neutral, with happiness being the most prevalent emotion, providing a baseline for random guessing of 24.4%.


This project will use CNN machine learning Algorithms and the following libraries:

pandas - for reading the data file
numpy - for arrays
tensorflow - for building the model
sklearn - for splitting the dataset
matplotlib - for  plotting graphs
 
The dataset will be split into a training set and a Classification set. The training set will extract information to teach the type of emotions from several images and the classification set will determine according to classifier performance.

The images have to maintain the exact same property to ensure the best result i.e. size

For each algorithm, this data set will be split into different training, testing, and validation set, (80,10,10)%
For each algorithm, accuracy will be calculated.

This project’s result will be evaluated by the accuracy of these algorithms. We humans are not always right to detect someone’s emotion with our eyes. We make mistakes too many times. A computer program is not different from this. The optimum accuracy for this project will be expected to be 85-90%.
