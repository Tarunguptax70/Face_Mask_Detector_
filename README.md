
# Face Mask Detector

😷 Real-Time Face Mask Detector 🚀

This project uses AI and your webcam to detect if people are wearing face masks in real-time.

It draws a <font color="green">GREEN</font> box for "Mask" and a <font color="red">RED</font> box for "No Mask".

---------------------------------------------------------------------------------------------------------------------

_📦 What's Inside?_

detect_mask_video.py: 👈 This is the main script to run!

mask_detector.h5: The pre-trained Keras AI model.

requirement.txt: All the Python libraries you need.

train_mask_detector.py: (Optional) Use this to train your own model.

---------------------------------------------------------------------------------------------------------------------

🚀 How to Run (3 Steps)
1. Get OpenCV's Face Detector

   This project also needs OpenCV's default face detector.

   Create a new folder named face_detector.

   Download these two files and put them inside that folder:

   deploy.prototxt.txt

   res10_300x300_ssd_iter_140000.caffemodel

   (You can easily find these by searching for "opencv face detector caffemodel")

2. Install Libraries

   Open your terminal and run:

   Bash:
     pip install -r requirement.txt

3. Run the Detector!

   Make sure your webcam is connected and run:

   Bash:
     python detect_mask_video.py

   
A window will pop up with your video feed. Press 'q' to quit.

--------------------------------------------------------------------------------------------------------------------------

📊 Model Training
Here is the accuracy and loss plot from training the mask_detector.h5 model:
