# A-Deep-Network-Solution-Towards-Model-less-Obstacle-Avoidance
This project is based on the report entitled "A Deep-Network Solution Towards Model-less Obstacle Avoidance" produced by Lei Tai et al.

The project is built using Python and uses the VREP simulating software. A scene was created so that the robot can explore, its called Project_CNN_Final.
There is also a Python code(CreateTrainingData.py) which is used to train the CNN model, called the Brain of the Robot. The purpose of the script is to create scene data to train based on the keyboard action and image gathered by the robot. The script provides a UI that is controlled using the up, down, left and right keys of the keyboard to drive the robot within the scene. A picture is taken once a key is pressed and this is used to assign an action to the data in the image.
Training data is provided with this project.

Executing the project:
1. Load the VREP simulating software.
2. Open the scene n VREP.
3. Run the robot_controller.py script.

The robot_controller.py is the core of the project in terms of operations. It will first train the CNN model using the training data and then move to control the robot. Control will be based on the images captured as the robot moves about the scene with the intention of avoiding obstances. The UI will also open giving users manual control of the robot if it gets stuck.

