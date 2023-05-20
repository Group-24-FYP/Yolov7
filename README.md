# run this command for infere using CPU

python detect_or_track.py --source F:/Education/FYP/Cam/code/brush.mp4 --track --device cpu --classes 79
 
# CUDA

python detect_or_track.py --source F:/Education/FYP/Cam/code/brush.mp4 --track --classes 79


## The inferred video stream with the bounding boxes will be saved to ..\yolov7\runs\detect

## The detected objects will be saved to ..\yolov7\objects