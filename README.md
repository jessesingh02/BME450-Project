# BME450-project

# Title
Shot Detection

## Team members
Kushal Muthamsetty (kushalmuthamsetty), Jaskaran Singh (jessesingh02)

## Project Description
In this project, we develop a deep learning model that classifies basketball shot attempts as either a make or a miss using video data. The goal is to train a model that can learn visual patterns associated with successful and unsuccessful shot attempts, enabling automated analysis of basketball scoring.

The input to the model consists of video clips, where each clip contains a single shot attempt. A deep learning model combined with a temporal model like an LSTM, is used to extract spatial features from individual frames and capture motion information across the sequence. Based on these learned features, the model predicts whether the shot results in a made basket or a miss. The dataset will be divided into training and testing sets. The training data will be used to teach the model to recognize patterns associated with made and missed shots, while the testing data will be used to evaluate how well the model categorizes new examples. Model performance will be assessed using metrics such as accuracy and precision.

