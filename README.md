# Tensorflow Face Detector

## Features
Speed, run 60fps on a nvidia GTX1080 GPU.

Memory, requires less than 364Mb GPU memory for single inference.



### Run video detection
At the source root
```bash
python inference_video_face.py
```
After finished the processing, find the output video at media folder.


### Run detection from usb camera

You can see how this face detection works with your web camera.
```
usage:inference_usbCam_face.py (cameraID | filename)
```

Here is an example to use usb camera with cameraID=0.

```bash
python inference_usbCam_face.py 0
```

Note: this script does not save video.


This project is created by : Mohammad Tanzil Idrisi
For any assistance: tanzilidrisi68@gmail.com

