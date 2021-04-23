# Face recognition as Biometric Security with a Scalable Approach

**Folder hierarchy:**

<br>Face Recognition/CelebA/CelebAPre-processing.ipynb </br> (Data Preprocessing File) &nbsp;
<br>Face Recognition/CelebA/img_align_celeba </br>(Dataset link: https://drive.google.com/drive/folders/0B7EVK8r0v71pWEZsZE9oNnFzTm8)
<br>Face Recognition/CelebA/README - Dataset.txt</br> (Dataset Discription)
<br>../Anaconda3/envs/facenetEnv/Lib/site-packages/facenet/src/Find_Embeddings.ipynb</br> (To create the embeddings for face images)
<br>../Anaconda3/envs/facenetEnv/Lib/site-packages/facenet/src/CelebA_svm_10000.ipynb</br> (Face recognition for first 10,000 images)
<br>../Anaconda3/envs/facenetEnv/Lib/site-packages/facenet/src/CelebA_svm_20000.ipynb</br> (Face recognition for first 20,000 images)
<br>../Anaconda3/envs/facenetEnv/Lib/site-packages/facenet/src/CelebA_svm_50000.ipynb</br> (Face recognition for first 50,000 images)

**Problem Statement and Objectives**

AI-based facial identification technology is one of the most intuitive technologies and it is also improving with the time []. We have already seen so many applications of facial recognition itself. For example, unlocking a phone by using your face.
The question here is what if we have very large amount of data which is lakhs. Is the system capable of doing face recognition in this situation? If so, what is the number of images where it could work in a Robust, Efficient, and Accurate manner. What is the accuracy it is giving with large-scaled data and what is the number of images it is giving best results? These are questions we are going to answer from our project. 
In addition to this, it could make verification possible in the ‘Touchless’ world, considering the Covid-19 outbreak as well. Companies tend to adopt the AI based facial recognition system by leaving the traditional fingerprinting scanner behind. In order to get the advance systems like paying by face, verify identity by scanning face while entering to office, we need an efficient system which can implement face verification and recognition efficiently at scale. 
Here our purpose is to deal with scalability and Develop a facial recognition system which can be robust, efficient, and accurate in order to work with large scale data. In order to identify the person, we are implementing one to many comparisons which checks against the database to discover identity. We use FaceNet system for the purpose of face recognition as it gives the state-of-the-art performance. Get the embeddings of images first and feed it to the model for training and prediction. Build a model by using the embeddings of images in order to train the model capable of predicting an individual.

