# Spritle-object-tracking-and-trajectory-prediction

## Description

custom_object_tracking_trajectory_prediction.ipynb contains code for custom yolov5 model training, object tracking  and prediction.
detect.ipynb is used during inference by the model and stores bounding boxes as a pickle file.
Traffic.mp4 is the original input video.
object_detection.mp4 is the video created by the yolov5 model when Traffic.mp4 is passed as the input
data.pkl stores all the bounding boxes information for Traffic.mp4
best.pt is the best weight for the yolov5 model.
object_tracking_and_trajectory_prediction.mp4 is the result of the overlay of object tracking and trajectory prediction on Traffic.mp4