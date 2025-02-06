# Object Tracking Application
![header_mots](https://github.com/user-attachments/assets/310dbd52-ada2-4263-96c4-e490ce33fef7)
This application tracks moving objects in a video using OpenCV and Streamlit. It uses the MOG2 background subtractor to detect moving objects and draws a green rectangle around them.

## Features

- Upload a video file in MP4, AVI, MOV, or WMV format.
- Detect moving objects in the video using the MOG2 background subtractor.
- Draw green rectangles around detected objects.
- Display the processed video frames in the Streamlit app.

## Requirements

- streamlit
- opencv-python-headless
- numpy

You can install the required packages using the following command:

```sh
pip install -r requirements.txt



## Usage

1. Run the Streamlit app:
    ```sh
    streamlit run app.py
    ```
2. This App deployed on streamlit cloud.
3. Upload a video file and see the object tracking in action. [Here](https://objecttrackingprojectroute.streamlit.app/)
