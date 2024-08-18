# Face-Detection-Recognition
I am thrilled to share a project I completed in computer vision focused on Face Detection and Recognition! This was a key requirement in my @Instant Software Solutions Training AI program, and it proved to be incredibly valuable, teaching me a lot along the way. I’m excited to work on and share more upcoming projects!

Tools I Used:
1) Face Detection with MTCNN : 
MTCNN (Multi-task Cascaded Convolutional Networks) is used for detecting faces in images or video streams.

2) Face Recognition with FaceNet :
FaceNet is a deep learning model that creates a 128-dimensional embedding for each detected face. This embedding represents the features extracted from the face, allowing for comparison with other embeddings. For instance, vectors that are close may represent the same person, while those that are far apart indicate different individuals.

3) Classification with SVM (Support Vector Machine) : I utilized SVM to classify faces based on normalized face embeddings. The SVM is trained on labeled embeddings to effectively differentiate between individuals.

Overall Process :
Detected Faces: Used MTCNN to identify faces in the image.
Extract Features: Passed detected faces through FaceNet to obtain embeddings.
Classify: Employed SVM trained on the embeddings for face recognition/classification.

Project Accuracy:
Training Accuracy: 0.991
Test Accuracy: 0.98

Check out my code : https://www.kaggle.com/code/kareemsalama/face-detection-recognition

Special thanks to our instructors in the AI Instant Course, Eng: @Ahmed Hafez  and Eng : @Abdullah Wagih Engineer, for providing us with this valuable experience!

