## Eye detection

This model has been trained with yolov5 to detect eyes on webcam. 

You need torch 1.6.0 and torchvision 0.7.0 with Python 3.7.

Then, open the Terminal or the command promp :

    python detect.py --weights best.pt --img 416 --conf 0.1 --source 0


