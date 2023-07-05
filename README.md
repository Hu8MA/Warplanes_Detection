# Warplanes_Detection

In this work, the model have been suggested for detecting and classifying five categories. The model is the CNNs training with (Yolo 7) architecture. This model can detect, localize, and classify multiple objects in still image and video tracking .The neural network was trained with more than 6,000 images, and obtained a good results, the (Yolo 7) architecture was also used in discovery and tracking, as it was built using the Python language. The images used in training and testing were of a size of 640 * 640.

#Results :-
Good results were obtained in detecting the object inside the image or inside the video, and this is considered an achievement despite the lack of data and the problems encountered in training the architecture.

#Problems:
Since the architecture is pre-trained, this is the cause of compatibility problems, because the data I work on is different in terms of entities, so problems occurred during training. It required that the project be only in the field of object discovery and not classification, because the architecture was built in a coherent and inflexible manner. Also, one of the problems is the effect of the initial weights, given that it was for pre-trained data (80 objects), this is the cause of problems in updating the weights (I mean that updating the weights was not at the required level) and this is the reason that in some cases the artificial intelligence detects (a person or a car) on It is one of the required elements and this is wrong. In the future we hope to do a reconstruction of this project where we expand the data set and also add solutions to these problems

#Note
1 Since I have lifted the weights, therefore, when using the code, you do not need to do training, just do a discovery (i.e. step 7, you do not need to implement it)

2 Pay attention to the paths because the code deals with data found in (Google Drive)
