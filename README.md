# Hand_Gesture_Recognitio_for_Cursor_Controlling
## Hand Gesture Recognition for Controlling Computer's Mouse Cursor
This is a Python project for controlling a computer's mouse cursor using hand gestures. The program recognizes hand gestures through a webcam using the Mediapipe library and controls the mouse cursor via the PyAutoGUI library.

The project is divided into two files, `app.py` and `controller.py`. The `app.py` file contains the main program logic while `controller.py` is responsible for handling the mouse cursor movement and click events.

There is an extra file, `requirements.txt` which you can use to install the libraries required for this project.

## Requirements
#### To run the program, the following libraries are required:<br>
  - OpenCV<br>
  - Mediapipe<br>
  - PyAutoGUI<br>
 
#### You can install these libraries using pip:<br>
  -  `pip install opencv-python mediapipe pyautogui`<br>
#### Or you can use the following command using pip to avoid any library version issue:<br>
  - `pip install -r requirements.txt`

## How to Run
After installing the required libraries, run the `app.py` file in a Python environment with a webcam. The program will start capturing video from the webcam, and the mouse cursor can be controlled using the following hand gestures:

  - **Cursor moving**: Raise all fingers together and move your hand to move the cursor and control it.<br><br>
      &nbsp;&nbsp;&nbsp;&nbsp; ![Mouse_moving](https://github.com/Himanshutiwari93/Hand_Gesture_Recognitio_for_Cursor_Controlling/assets/113496568/3c37e63b-b317-42f4-9b85-1d38c54d6f2d)

  - **Cursor freezing**: Close your thumb and Raise all other fingers together freeze the cursor and prevent it from moving.<br><br>
       &nbsp;&nbsp;&nbsp;&nbsp; ![Mouse_freezing](https://github.com/Himanshutiwari93/Hand_Gesture_Recognitio_for_Cursor_Controlling/assets/113496568/8130c612-47fc-49d7-8f61-45efb3cf67f8)

  - **Drag and drop**: Close your hand into a fist and move it around to drag and drop objects.<br><br>
      &nbsp;&nbsp;&nbsp;&nbsp; ![Drag](https://github.com/Himanshutiwari93/Hand_Gesture_Recognitio_for_Cursor_Controlling/assets/113496568/7d3992db-28f5-43d0-adac-26dc89e92527)

  - **Right-click**: Raise your index finger while keeping the other fingers closed.<br><br>
       &nbsp;&nbsp;&nbsp;&nbsp; ![Right_click](https://github.com/Himanshutiwari93/Hand_Gesture_Recognitio_for_Cursor_Controlling/assets/113496568/7c7f8f83-7d05-490a-b5c1-e906e7f5e8af)

  - **Left-click**: Raise your middle finger while keeping the other fingers closed.<br><br>
      &nbsp;&nbsp;&nbsp;&nbsp; ![Left_click](https://github.com/Himanshutiwari93/Hand_Gesture_Recognitio_for_Cursor_Controlling/assets/113496568/ab0bc51f-cadd-4cd9-a593-625c207a5e55)

  - **Double-click**: Raise your index and middle finger while keeping the other fingers closed.<br><br>
       &nbsp;&nbsp;&nbsp;&nbsp; ![Double_click](https://github.com/Himanshutiwari93/Hand_Gesture_Recognitio_for_Cursor_Controlling/assets/113496568/3c4337f5-836c-4c33-b011-317c5627acfa)

  - **Scroll up**: Move your index and middle finger towards the screen.<br><br>
       &nbsp;&nbsp;&nbsp;&nbsp; ![Scrolling_up](https://github.com/Himanshutiwari93/Hand_Gesture_Recognitio_for_Cursor_Controlling/assets/113496568/4bf149ec-284d-4a9b-bee5-66fba8856cf6)

  - **Scroll down**: Move your index and middle finger away from the screen.<br><br>
      &nbsp;&nbsp;&nbsp;&nbsp; ![Scrolling_down](https://github.com/Himanshutiwari93/Hand_Gesture_Recognitio_for_Cursor_Controlling/assets/113496568/118c8fd7-2a22-4515-8c43-ca6b68a2d9f7)

  - **Zoom in**: Pinch your index finger and thumb together.<br><br>
     &nbsp;&nbsp;&nbsp;&nbsp; ![Zooming_in](https://github.com/Himanshutiwari93/Hand_Gesture_Recognitio_for_Cursor_Controlling/assets/113496568/dc449d50-6701-4127-9733-e157aace7aa7)

  - **Zoom out**: Spread your index finger and thumb apart.<br><br>
        &nbsp;&nbsp;&nbsp;&nbsp; ![Zooming_out](https://github.com/Himanshutiwari93/Hand_Gesture_Recognitio_for_Cursor_Controlling/assets/113496568/77fea04f-1d15-4f30-8510-7a081a0f8c79)

## How it Works
The program uses the Mediapipe library to detect hand landmarks from the video captured by the webcam. The `controller.py` file contains the logic for mapping the hand landmarks to specific mouse cursor actions, such as movement and clicking.

## Limitations
The program currently only supports controlling a single mouse cursor, and it may not work well in low-light conditions. It also doesn't support handling gestures of more than one hand, however this is easy to overcome, may be in comming commits of this project.

## License

This project is licensed under the Apache License 2.0. The Apache License 2.0 is a permissive license that allows you to freely use, modify, distribute, and sell the software.<br>

Feel free to use, modify and distribute the code as you see fit under the terms of the Apache License 2.0. For more information, please refer to the LICENSE file in the root of the project directory.
