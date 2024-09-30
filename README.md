>Description
Hi welcome to my new deep learning project "Yoga Asana Classifier / pose classifier ". This project as the name suggests can predict the yoga pose which you are doing in front of the webcam.
This project comprise of three python scripts namely,
Data Collection
Data Training<
And finally Inference script.
As all of the name suggest do there respective work.

For this project I used mediapipe pose detection to detect the human body pose and after that I made model with simple Dense network using keras and trained the model on the data. After that i just ran the inference file to do the prediction.
Requirements
pip install mediapipe
pip install keras
pip install tensorflow
pip install opencv-python
pip install numpy

How to Run?
Adding Data<
  To add data you have to run python data_collection.py and  have to provide the name of asana you want to add.
 Training
  To train just run python data_training.py to train the model on newly added data.
  Running
  To Run just run python inference.py and new window will pop up which will be running the predictions.
  
  
