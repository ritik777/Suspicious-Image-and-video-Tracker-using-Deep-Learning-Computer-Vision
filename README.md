# Suspicious-Image-and-video-Tracker-using-Deep-Learning-Computer-Vision
Please read through ReadMe.docx that will make run the project on the machine with sufficient memory requirements.

# Video Link
https://www.youtube.com/watch?reload=9&v=XGTTGuKL39U&feature=youtu.be

# Introduction
Facial recognition and activity detection in the area of online video and image surveillance is
becoming a more and more popular and accessible biometric method to enhance computer
applications and detect various patterns that will help in anomaly detection in case of people
and events, suspicious e-Crime, terrorist account detection, ATM and bank fraud, and
intelligent video surveillance systems especially because of factors like Social Media trends,
increasing number of eLearning courses and exams, and distance learning management
systems to name a few.

# Methodology for our experimentation
In order to detect suspicious activity based on head and eye movements, we divided our
problem into 2 parts each of which has varying levels of complexity.

Part 1 : We collected our own data of images and labelled them as clean and suspicious accordingly
Part 2 : we collected burst of videos and based on frame reference we checked image classification on each frame of a video from part1 and labeled suspicious or clean

# Data Collection:
We created our own dataset by trying to replicate the online exam scenario and captured
different images and videos of friends, batchmates and family

# Level of Complexity 
Part 1-Images:
o Level-1: We start off with classifying extreme head movements as suspicious
and no head movement as clean i.e., a person would be labelled suspicious if
he/she is not looking into the screen and looking away.

o Level-2: For the second level, we increase complexity by trying to classify
subtly angled head movements (ex. At 30°, 45°, etc) as suspicious and no
movement as clean.

o Level-3: For the third level, we try capturing eye movements of the person to
classify their activity as suspicious or clean

Part 2-Videos:
o Level-1: We classify the entire video as suspicious or clean based on a predefined cut-off or threshold value (in our case we used 0.5 as cutoff)

o Level-2: We classify the videos by flagging or extracting parts/intervals of the
video as suspicious or clean.

# Libraries used in Python
Numpy, Pandas,OpenCV, Matplotlib, Scikitlearn, Tensorflow and Keras. 

Please go through the report to have a look at our entire work.
