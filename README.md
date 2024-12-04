To complete the execution of this project we require some packages so we have to install those packages.
first we need to check the python version in command prompt using python --version
if the python version is 3.12.7
package         version
cmake           3.31.1
dlib            19.24.99
imutils         0.5.4
numpy           1.26.3
opencv-python   4.10.0.84
pip             24.3.1
playsound       1.3.0
setuptools      75.6.0
wheel           0.45.1

COMMANDS TO INSTALL THE ABOVE PACKAGES:
pip install cmake
python3 -m pip install imutils
pip install opencv-python
when we install this opencv we get numpy also.
before installing playsound we have to upgrade setup tools
pip install --upgrade setuptools
pip install playsound
pip install <copy and paste the dlib zip file name>.whl
to check the installed packages
pip list
now run the file using by setting the path
if we get any image error while execution
check numpy version if the numpy version >=2 then uninstall the numpy using 
pip uninstall numpy
after uninstalling numpy then install
pip install numpy==1.26.3
this is are the commands used for execution of the project
