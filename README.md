===============================================README====================================================

This project trains a robotic hand to play the piano using deep reinforcement learning. 
The following main python libraries and their versions are needed to run the given code: 

python == 3.7.6 
pip == 20.0.2 
imageio == 2.6.1 
ipynb == 0.5.1 
numpy == 1.18.1 
gym == 0.17.2 
pillow == 7.0.0 
pybullet == 3.0.6 
tensorflow == 2.3.1 
keras == 2.4.0 
matplotlib == 3.1.3 
tensorboard == 2.4.0

 

========================================Files and their descriptions:======================================

PianoHandv1.ipynb: This is the Jupyter notebook containing our environment.
 
UnitTests.ipynb: This is the Jupyter notebook containing tests to check the functioning of the environment.
 
TrainingWithActorCriticMethod.ipynb: This is the Jupyter notebook containing the training code for our agent.
 
Validation.ipynb: This is the Jupyter notebook containing the code to validate our trained model.
 
ComparisonWithOtherAlgorithms.ipynb: This is the Jupyter notebook to compare the performance to other 
conventional algorithms such as SARSA and PID Control. 

3DRenderUsingPybullet: This is the Jupyter notebook containing the code for rendering our 3D model to get 
a visual demonstration of the agent. 

TrainingWithDQN-SuboptimalTraining.ipynb:  This is the Jupyter notebook containing the training code that was 
used to try and train the agent with DQN, which produced suboptimal results. 

Requirements.txt: This file lists the python version, and the versions of the python libraries used to run the code. 

 

======================================Directories and their contents:=========================================

Weights: Contains the best weights obtained after training the robotic hand to reach two of the goals – key C 
and key D. These weights are used to demonstrate the learning in the validation code. 

GIFS: Contains typical examples gifs of playing a wrong and right key. (examplerightkey.gif, examplewrongkey.gif). 
Contains preloaded validated gifs such as PreloadedC.gif and PreloadedD.gif). After the validation code is executed, 
the validated gifs are also saved in this directory.It also contains the gif of the 3DRender using Pybullet. 

Pictures: Contains the necessary pictures which are imported in jupyter notebooks to better the explanations. 

Fonts: Contains the required font to implement the render methods. 

Hand: Contains the urdf file of the 3D-CAD of piano to import in the 3DRender using Pybullet. 

Piano: Contains the urdf file of the 3D-CAD of piano to import in the 3DRender using Pybullet. 

Logs: Holds the tensorboard logs while training. 