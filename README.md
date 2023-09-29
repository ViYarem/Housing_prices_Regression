# EfficientNetB0_yoga_images_classification
For Kaggle competition https://www.kaggle.com/competitions/ukraine-ml-bootcamp-2023/overview


# About the competition
Yoga has gained popularity in the past couple of decades and because of its success in making people physically and mentally fit, it has become widely popular all over the world. Especially in the last 2 years after the pandemic hit the world, people have been spending most of their time in their homes which opens up more suitable conditions and possibilities of practicing yoga.

However, it is very important to stretch the body correctly in every asana as each yoga pose targets a specific muscle of your body and the problem with yoga is that, just like any other exercise, it is of utmost importance to practice it correctly as any incorrect posture during a yoga session can be unproductive and possibly detrimental.

Human pose estimation is a well-known problem in computer vision to locate joint positions. The application of pose estimation for yoga is challenging as it involves a complex configuration of postures. Furthermore, some state-of-the-art methods fail to perform well when the asana involves horizontal body posture or when both the legs overlap each other or any similar complex pose.

In this competition, we formulate the pose estimation as a classification task and you will have to classify different yoga asanas into different classes. You will be responsible for creating algorithms capable of performing a precise classification by aiming for higher Mean F1 scores. The dataset has pictures of different yoga poses and the class to which it belongs. There are a total of 6 classes based on the posture of the person performing the asana. Evaluation of your algorithms would be based on the Mean F1 score.

# About the data set
The dataset provided in the train.csv consists of the following features:

image_id: The unique ID for each image of yoga pose.
class_6: The class to which each yoga pose image belongs. (target variable)

# Evaluation Metrics
The evaluation metric for this competition is Mean F1-Score. The F1 score, commonly used in information retrieval, measures accuracy using the statistics precision "p" and recall "r". Submissions are evaluated on MeanFScore, which at Kaggle is actually a micro-averaged F1-score.

The F1 metric weights recall and precision equally, and a good retrieval algorithm will maximize both precision and recall simultaneously. Thus, moderately good performance on both will be favored over extremely good performance on one and poor performance on the other.

# Submission Format
For every image_id in the dataset, the submission file should contain two columns: image_id which is the unique id for each image from the testing images, and class_6 which is the class value to which the image belongs. The second column should be a space-delimited string value.
