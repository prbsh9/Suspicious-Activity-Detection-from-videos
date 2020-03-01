# Suspicious-Activity-Detection-from-videos

### Extract frames from the video:
get_frames_from_video.ipynb - extract frames to their respective dir from video dataset.

### Way1 Plain CNN
ImageclassifierCNN.ipynb- update required.. tried with CNN using keras/tf and a image as a single data of either normal or abnormal.<br>
suspiciousDetectionFastai.ipynb - Used CNN to do the work using a frame as a single data point and used FastAI to do the task.
<br><br>

## Way2 CNN + RNN
After getting frames:
Small_frames_to_feature_map.ipynb - you can store the high level featuremap of the frames in npy file through directory of frames,        but just done to small dataset. <br>
big_frames_to_feature_map.ipynb - just bigger version of Small_frames_to_feature_map.ipynb.
<br><br>

After getting npy file: <br>
Small_RNNImageClassifier.ipynb - Predict from the numpy file of small dataset as dummy dataset of around 15 GB.
RNNImageClassifier.ipynb - Predict from the numpy file of dataset using LSTM.

## Other files
1.csv<br>
2.csv<br>
3.csv<br>
4.csv<br>
final.csv<br>
These CSV files helps us to get frames of the video in correct order easily.
<br>
## completing soon
