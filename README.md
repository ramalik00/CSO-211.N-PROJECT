# CSO-211.N-PROJECT(Face-Mask-Detector)
  This is project under CSO 211(COMPUTER SYSTEM ORGANIZATION) aimed at using Computer Vision to detect face mask in real time.The detector created is pretty   accurate, and since we used the MobileNetV2 architecture, it’s also computationally efficient and can be used in embeded systems.This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.

## Project Structure
  #### The structure of the project was as follows -
  1. The project uses caffe based implementation for face and gender detection . The gender detection model is work by Gil Levi and Tal Hassner. Link to the [research paper](https://talhassner.github.io/home/publication/2015_CVPR)
  2. A model was trained on the dataset in the links below to sucessfully detect mask on the face using Keras 
  3. The project was then deployed using KivyMD for simple desktop based use .
  4. To improve the fps we have used a custom based I/O technique using threading and added FPS count implementation to calculate fps.
  

## 🚀&nbsp; Installation
1. Clone the repo
```
$ git clone https://github.com/ramalik00/CSO-211.N-PROJECT
```

2. Change your directory to the cloned repo and create a Python virtual environment named 'test' or anything you wish. Prefer this option if you want to directly test it using the terminal otherwise install all the dependencies directly on you machine 
```
$ mkvirtualenv test
```

3. Now, run the following command in your Terminal/Command Prompt to install the libraries required
```
$ pip3 install -r requirements.txt
```
4. Refer to this [link](https://kivy.org/doc/stable/installation/installation-linux.html) for installing kivy 

5. Also run the following command as well
```
$ pip3 install opencv-contrib-python
$ python3 -m pip install kivymd
```
## Running the project on your System
   1. First install all the dependencies listed in the installation part . 
   2. Now simply use the following command
   ```
   $ python3 app.py  
   ```
## FRAME RATE PER SECOND 
   1. To analyze frames rate per second run the following command
   ```
   $ python3 Fps_Analysis.py  
   ```

## Team
- Rahul Malik [@ramalik00](https://github.com/ramalik00)
- Saatvik Sharma [@saatvik10](https://github.com/saatvik10)
- Shivansh Sood [@godfather2603](https://github.com/godfather2603)
- Naman Arora [@Naman-Arora23](https://github.com/Naman-Arora23)

> The project is currently **in progress**.
