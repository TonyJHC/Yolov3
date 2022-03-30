#<strong>Yolov3_video.avi with raspberrypi</strong>

##Build a development environment
-pyhton 3.7.7
-pip install tensorflow==2.0.0
 (if you own CUDA GPU: pip install tensorflow-gpu==2.0.0)
-pip install opencv-python
-go to website and download weights file: pjreddie.com/media/files/yolov3.weights
-go to github sit and download code zip:github.com/zzh8829/yolov3-tf2V
 (After unpacking copy 'yolov3.weights' file and paste 'data' floder)
-go to unzipped path and open cmd(command prompt)
-covert weights files : python conver.py
-python detect_video.py --video 0(using a webcam)

###result
I ran the Yolov3 code for object recognition.
-CPU: 700ms(intelcore-i7(10th))
-GPU: 70ms (RTX2060 on notebook)
The speed of object recognition between the CPU and GPU was about 10 times different.

