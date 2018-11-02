# A-framework-for-CPR-scene-retrieval-from-medical-simulation-videos-based-on-activity-detection

# Keywords:
Video segmentation , Region of interest extraction , Face detection , Spatio-temporal histogram of oriented gradients - HOG3D, Local binary patterns - three orthogonal planes - LBP-TOP , 3D Scale-invariant feature transform (SIFT-3D) , Classifier fusion

# Abstract:
Medical simulations, where uncommon clinical situations can be replicated, have
proved to provide a more comprehensive training. Simulations involve the use of
patient simulators, which are lifelike mannequins. After each session, the physician
must manually review and annotate the recordings and then debrief the trainees.
This process can be tedious and retrieval of specific video segments should be automated.
In this project, we present activity based scene retrieval framework to detect and
classify scenes that involve Cardio-Pulmonary Resuscitation (CPR) activity from
training video sessions simulating medical crises.
The first step of our approach consists of segmenting the video into overlapping
volumes. Then from each volume, we extract the region of interest which is the
chest of the lifelike mannequin since if a CPR activity is taking place, the hands
of the trainee will be placed on the center of the chest of lifelike mannequin. To
reduce the computational complexity of our approach we discard from processing
volumes which don’t have significant motion in the region of interest and to im-
prove the efficiency of our framework, we detect the nearest head to the region of
interest in order to analyze its motion in addition to the motion of the hands.
After extracting two sub-volumes from each volume, we describe them using spatio-
temporal features: histogram of oriented gradients 3D, local binary patterns-three
orthogonal planes and scale-invariant feature transform 3D. Then, we use Support
Vector Machine (SVM) and K Nearest Neighbors (KNN) classifiers for classifica-
tion and finally we fuse all the information obtained from different classifiers to
decide finally for each video volume if it belongs to CPR scene or not.
The proposed framework is tested and validated using two simulation videos and
the experimental results are presented.

# The code is available on reasonable request (Matlab)
 
