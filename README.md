<h1> Human Falling Detection and Tracking </h1>

https://www.youtube.com/watch?v=JAD4GwLtgQ0&t=82s

Fall recognition

Python 3 

Originally built/tested on TF/Pycharm

Default testing clip included in the package, adjust parameters in main file to test different clips or image

Using Tiny-YOLO oneclass to detect each person in the frame and use 
[AlphaPose](https://github.com/MVIG-SJTU/AlphaPose) to get skeleton-pose and then use
[ST-GCN](https://github.com/yysijie/st-gcn) model to predict action from every 30 frames 
of each person tracks.

Project made just for fun
