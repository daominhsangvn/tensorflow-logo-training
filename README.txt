## Prerequisites:
1. Python 3.7+
2. LableImg: 
 - Download labelImg from https://github.com/tzutalin/labelImg and put into folder `labelImg`
 - Install Anaconda: https://www.anaconda.com/
 - Open Anaconda from Start Menu
 - Cd to labelImage folder
 - `conda install pyqt=5`
 - `conda install -c anaconda lxml`
 - `pyrcc5 -o libs/resources.py resources.qrc`

## Begin Training Data
1. Prepare images:
Try to find as much as image that contains the object in many different backgrounds. You can use this lib to download batch of image from google https://github.com/hardikvasa/google-images-download
2. Labeling images:
 - Create new folder `annotations` in your project
 - Start labelImage: `python labelImg.py` or start with specific file `python labelImg.py [IMAGE_PATH] [PRE-DEFINED CLASS FILE]`