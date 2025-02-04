# Pothole-detection-with-combined-CNN-PSO
The work is done for detecting potholes with the combination of CNN algoritms and convolutional layers.

# -Abstract
<p align="justify"> Poor road maintenance leads to potholes on the road. Potholes are responsi-
ble for road accidents and even deaths in developed and developing countries.
Detecting and filling road potholes is an essential part of road maintenance.
Sustaining a reliable and safe road for communication depends on pothole
detection. This study presents a novel combination of a convolutional neural
network and an optimized machine-learning model by a heuristic algorithm
for pothole detection. The proposed method comprises a shallow convolu-
tional neural network for feature extraction and an optimized random forest
model for pothole detection. The proposed model initially uses the shallow
convolutional layer to extract feature sets from input pictures. Then, the
particle swarm optimizer is used to eliminate irrelevant features. Finally, a
combination of random forest and a particle swarm optimizer is used for pot-
hole detection. Particle swarm optimization indicates the best subset of the
extracted feature set for final pothole detection. We added 171 pictures to
the already available 665 pothole pictures to evaluate the proposed method.
The test set was isolated from the training set, and we trained the model on
k-fold cross-validation. The experimental result indicates 99.37% accuracy,
99.37% precision, 99.38% sensitivity, and 99.38% F1-score for discriminating
potholes from roads without potholes by proposed methods. The response
time of the proposed method for pothole detection is 0.02 seconds. The
proposed method can be utilized for real-time pothole detection.</p>

# -Evaluation Results 
# AUROC Results
![AUROC+RF](https://github.com/user-attachments/assets/441ba272-12f4-47f2-8bc8-c5f4a4c7df63)
![AUROC+XGB](https://github.com/user-attachments/assets/b812b209-e06d-4580-8714-5ab6dfcaa8cc)
# Confusion Matrix Results
![RF+PSO (2)](https://github.com/user-attachments/assets/8871f515-c1cb-4cca-a755-5434e90eff97)
![XGB+SO](https://github.com/user-attachments/assets/6296f3fe-23f9-4c62-a98b-f48d2a21e82f)


