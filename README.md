# Object Tracking Application
<<<<<<< HEAD
![alt text](image.png)
=======
![image](https://github.com/user-attachments/assets/a611c725-6103-42bf-9493-984a567ddce9)
>>>>>>> 57731d3027f09229d2ec171b72f361af88a5a143
This application tracks moving objects in a video using OpenCV and Streamlit. It uses the MOG2 background subtractor to detect moving objects and draws a green rectangle around them.

## Features

- Upload a video file in MP4, AVI, MOV, or WMV format.
- Detect moving objects in the video using the MOG2 background subtractor.
- Draw green rectangles around detected objects.
- Display the processed video frames in the Streamlit app.

## Usage

1. Run the Streamlit app:
    ```sh
    streamlit run app.py
    ```
2. This App deployed on streamlit cloud.
3. Upload a video file and see the object tracking in action. [Here](https://objecttrackingprojectaymon.streamlit.app/)

## Requirements

- streamlit
- opencv-python-headless
- numpy

You can install the required packages using the following command:

```sh
pip install -r requirements.txt
