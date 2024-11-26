Detecting, Localizing, and Tracking Vehicle
The goal of this project is to implement a complete pipeline to detect, localize,and track vehicles.  
The pipeline will consist of a number of steps:  (1) a datasetsetup  (2)  a  classifier ,  (3)  a  detector  and  localizer, and (4) an object tracker.  
A partial training and validation set sourced from the KITTI vision benchmark: https://www.cvlibs.net/datasets/kitti/
The  training  dataset provided  contains  three  training  video  sequences(A) 0000, (B) 0001, and (C) 0002.  All videos are provided at fixed resolutionof 1242x375.  Bounding box annotations are provided for the above mentionedthree difference video sequences.  
It is required to parse a ground truth0000.txt,0001.txt, and0002.txtfiles associated with each video sequence in or-der to extract bounding box information for a specific sequence on a frame byframe basis.
