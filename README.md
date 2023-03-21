# Autonomous Driving using Imitation Learning
 
We used the carla version 0.9.8 for windows. It uses python 3.7. To run the project you have to download carla version 0.9.8 from [here](https://github.com/carla-simulator/carla/releases/tag/0.9.8/) .
Then copy the file **examples/project.py** to **WindowsNoEditor/PythonAPI/examples/** in downloaded Carla folder. Run the file **CarlaUE4.exe** to run carla server and then navigate to **WindowsNoEditor/PythonAPI/examples/** and run the following command<br />
`py -3.7 project.py` <br />
Command line will show all available control keys to collect image, to change the car to self driving mode etc. Another pygame window will open where the simulation will take place. 
Before running the server and client, replace the **requirement.txt** file in **WindowsNoEditor/PythonAPI/examples/** with our **requirement.txt** and install the requirements.

## Data Collection
We collected 2 hours driving data. In total 10.5k images were collected but used only 5.6k images.
Among them we used 3.6k images for training and 2k images for validation.

## Demo 
![alt text][logo]

[logo]: https://github.com/dragnil1/Autonomous-Driving-using-Imitation-Learning/blob/main/demo.gif "Demo"
