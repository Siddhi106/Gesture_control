This is a Python project for controlling a computer's mouse cursor using hand gestures. The program recognizes hand gestures through a webcam using the Mediapipe library and controls the mouse cursor via the PyAutoGUI library.

The project is divided into two files, app.py and controller.py. The app.py file contains the main program logic while controller.py is responsible for handling the mouse cursor movement and click events.

There is an extra file, requirements.txt which you can use to install the libraries required for this project.

How to Run After installing the required libraries, run the app.py file in a Python environment with a webcam. The program will start capturing video from the webcam, and the mouse cursor can be controlled using the following hand gestures:

Cursor moving: Raise all fingers together and move your hand to move the cursor and control it.

 Mouse_moving
Cursor freezing: Close your thumb and Raise all other fingers together freeze the cursor and prevent it from moving.

 Mouse_freezing
Drag and drop: Close your hand into a fist and move it around to drag and drop objects.

 Drag
Right-click: Raise your index finger while keeping the other fingers closed.

 Right_click
Left-click: Raise your middle finger while keeping the other fingers closed.

 Left_click
Double-click: Raise your index and middle finger while keeping the other fingers closed.

 Double_click
Scroll up: Move your index and middle finger towards the screen.

 Scrolling_up
Scroll down: Move your index and middle finger away from the screen.

 Scrolling_down
Zoom in: Pinch your index finger and thumb together.

 Zooming_in
Zoom out: Spread your index finger and thumb apart.

 Zooming_out
