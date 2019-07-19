Hello everyone, in this project i use Pycharm and Anaconda Enviroment
This is an usefull link to set up pycharm and anaconda, https://medium.com/infinity-aka-aseem/how-to-setup-pycharm-with-an-anaconda-virtual-environment-already-created-fb927bacbe61

Then you should install keras library (with tensorflow backend) and pygame,  after than you should go to anaconda terminal and follow the following steps:



1st: conda install python=3.6



2nd: conda create --name PythonGPU (Ensure that you have a NVIDIA graphics card.)



If you don’t, install the CPU version of Keras.


2nd: conda create --name PythonCPU


To activate the conda environment (PythonCPU/Python GPU) follow the following procedure:


3rd: activate PythonGPU or activate PythonCPU

To deactivate the environment(PythonCPU/Python GPU) use: 

conda deactivate

!!Do not deactivate the environment yet


4th: conda install -c anaconda keras-gpu (or conda install -c anaconda keras)

!!!!!! DO NOT INSTALL PYGAME BEFORE ALL THIS THINGS 


5th: pip install pygame 


ENJOY!!!!
