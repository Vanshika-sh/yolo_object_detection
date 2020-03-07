# yolo_object_detection
YOLO object detection performed on images, videos and in real time.

To run on images:
File: yolo.py
Command: $ python yolo.py --image images/[image_name].jpg --yolo yolo-coco

To run on videos:
File: yolo_video.py 
Command: $ python yolo_video.py --input videos/[video_name].mp4 --output output/[output_video_name].avi --yolo yolo-coco
  
For real time execution:
File: realtime_yolo.py
Command: $ python realtime_yolo.py --output output/[output].avi --yolo yolo-coco
