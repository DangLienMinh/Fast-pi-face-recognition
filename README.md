# Fast-raspberry-pi-face-detection-and-recognition
Raspberry pi face detection and recognition with face rotational invariance

If you have just set up the raspberry and the camera. Then please follow this [**tutorials**](http://www.pyimagesearch.com/2016/04/18/install-guide-raspberry-pi-3-raspbian-jessie-opencv-3/) for installing opencv and python. That a very good starting point.

Environment:
- Raspberry Pi 3 + Raspberry pi camera V2
- OpenCV 3.1.0
- Python 2.7.9

**Implement:**
1. Open the dataset folder for sample images, the format in this dataset folder is User.[id].[index]. For example: User.1.43 is User with id=1 and the index of the image is 43. You should capture the user image in different expression, possition, lightning condition like in the dataset.
![]({{site.baseurl}}//upload//2017-04-01-154913_1184x624_scrot.png)
P/S: Open changeImageName, you can put all image of a user to image_here folder to change the image name format. Open changename.py and edit the image name format as you want then put the images back to dataset folder.
![]({{site.baseurl}}//2017-04-01-155213_1184x624_scrot.png)
2. After colletecting the dataset please run: python trainer.py to train the images
![]({{site.baseurl}}//2017-04-01-155423_1184x624_scrot.png)
3. After completing the training, please run: python FaceRecognizer.py to fire up the camera
![]({{site.baseurl}}//2017-04-01-155503_1184x624_scrot.png)
![]({{site.baseurl}}//2017-04-01-155547_1184x624_scrot.png)
![]({{site.baseurl}}//2017-04-01-155602_1184x624_scrot.png)
