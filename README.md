# osy_project_weapon_detection
This project allows to run the gun detection model from your webcam.

# Installation
Run `pip install -r requirements.txt` from main project directory to install all necessary modules.
You can run it from a virtual environment.

# Run
Run `python3 webcam_object_detection.py` from main project directory.
It will open a new window showing images of your webcam.
On each image it will show a green bounding box around what it considers as a handgun.

# Use on a different model
To use this on a different model, you need to 

* Put the whole inference folder into the project
* Change the `PATH_TO_CKPT` variable in `webcam_object_detection`
* If necessary, change the label path and number of classes.
