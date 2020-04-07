# how to run this program:

   Install Python 3.xx
   
   - Make Virtual Environment
   - python3 -m venv tensorflowDetection ( you can change this name )
   - Active your Virtual Environment source /bin/activate
   - download models from https://github.com/tensorflow/models ( include in your Environment )
   - Tensorflow Object Detection API depends on the following libraries & install on your Environment :
    
    numpy
    opencv-python
    Protobuf 3.0.0
    Python-tk
    Pillow 1.0
    lxml
    tf Slim (which is included in the "tensorflow/models/research/" checkout)
    Jupyter notebook
    Matplotlib
    Tensorflow (>=1.12.0)
    Cython
    contextlib2
    cocoapi
   
   - From tensorflow/models/research/
   
     protoc object_detection/protos/*.proto --python_out=.
    
   - modified this code and save into tensorflow/models/research/ and run
   
   # For more information about installation tensorFlow
   
   https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md
    
   Happy Coding


