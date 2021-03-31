# Road-Sign-Detection-using-CNN

1.download GTSB dataset from following link:

https://benchmark.ini.rub.de/gtsdb_dataset.html
Note:
  download following files
	1.FullIJCNN2013.zip
	2.gt.txt
(i have stored the dataset in maindata directry)

2.save the images in yolo format required for training
(ie. jpg image and text file with same name eg.1.jpg and 1.txt)

3.create train.txt,test.txt,data.data and classes.names file using the py files)

4.before training download the weights required for training

link-https://pjreddie.com/media/files/darknet53.conv.74

NOTE-configuration files required for training and testing are stored in training and testing folder

4.train the dataset using darknet
(clone the darknet repository on drive)
note:
i have used google colab for training so you need to store the files on drive)
(mount the drive)

weights will be stored in backup folder on drive so before
training create backup folder on drive

5.test the custom detector using opencv.

or if you have machine with darknet installed with gpu
then you can test custom detector on video directly on your machine)




