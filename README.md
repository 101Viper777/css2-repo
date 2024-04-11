## you need to have python installed to use this repo

also when u clone and activate the venv via: source env/bin/activate  , you need to pip install tensorflow

and cd yolov2test/darknet and run this code

wget https://pjreddie.com/media/files/yolov2.weights

then run this code to start training

./darknet detect cfg/yolov3.cfg yolov3.weights data/dog.jpg
