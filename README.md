# Project-computer-vision
##WELCOME TO OUR MARS ROVER PROJECT

Team members: ziad ashraf ahmed ahmed kasem 19p7095
		  Gannah Allah Mohamed GAber MAhmoud 19p9610
		  Yassin Khaled Mostafa Attia Mahgub 19p9597
		  Adham Ehab Salman Selim 19p4388
		  Mohamed Mahmoud Sadek Mahmoud Rehab 17P8053

The pipeline is shown in the jupyter notebook "Rover_Project_Test_Notebook.ipynb" within the code file
the notebook uses a random output image from the simulator and put it through the pipeline to show the
diffrent stages of the image proccessing.

when the simulator starts a realtime debugging mode is enabled to show the diffrent stages of the realtime
input image through the simulator run.

Use this link to download the simulator:
https://s3-us-west-1.amazonaws.com/udacity-robotics/Rover+Unity+Sims/Linux_Roversim.zip

To run the code a few steps must taken.
1)Set up enviroment; make sure following libraries must be included within your enviroment:
	-cv2
	-numpy
	-matplotlib
	-scipy
	-glob
	-imageio
	-time
	-PIL
	-io
	-base64

2)using the terminal activate the enviroment you will use only if it is any other library than the root enviorment
  using the command: conda ativate EnviromentName.

3)using the terminal from within the code file directory use the command: python drive_rover.py
  the initiates a server with code running within

4)launch the Roversim in autonmous mode and the rover will start exploring on its own. 	
