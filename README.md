![Darknet Logo](http://pjreddie.com/media/files/darknet-black-small.png)

#Darknet#
Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.

For more information see the [Darknet project website](http://pjreddie.com/darknet).

For questions or issues please use the [Google Group](https://groups.google.com/forum/#!forum/darknet).

How to USE.

gsutil cp gs://tsuchinoko traindata.tar.gz

tar xzvf traindata.tar.gz

./darknet detector train yolo.data cfg/yolo.2.0.cfg -gpus 1

./darknet yolo test cfg/yolo.2.0.cfg backup/yolo_final.weights testfile.jpg

