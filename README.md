# Masters-Project-Keyboard-Inference-via-Acoustic-Signals

Master-s-Project---Acoustic-Keyboard-Eavesdropping
Files and things related to my Master's Project.

Brief Project Overview: The overarching goal is to deduce keyboard inputs solely based on acoustic inputs only from typing sounds. The method I use is up to me, which gives me flexibility in researching and attempting different solutions to produce my desired goal. This project was chosen to provide me with a challenge since I am inexperienced in both signal processing and neural networks. I am hoping that challenging myself will help me learn and grow with my skills in Matlab, signal processing, neural networks, and being able to adapt to new topics unfamiliar to me. The project was also chosen since I found the challenge interesting.

Please watch the Introduction_Project Overview to learn about the project
Watch Code and Neural Network.mp4 to learn about the code or specific details on the neural network toolbox used for this project
Watch Project Continuation to learn about extending this project, or resuming where I originally left off 
All videos are in the Project Videos and Presentations Folder



List of Folders and what they contain:
The examples folder contains everything needed to use DeepSpeechRecognition.m, you can also find this example online to download and use, but I’ve provided it here for convenience

The Filtered_Extra folder contains letter data that I created with a filter that blocks out all noise, however this was never used. I decided that it was better to train data with ambient noise levels since it Is more practical in performing a real side channel attack.

NNSTART folder contains the code to actually run the neural network, it also has all the letter data (50 samples of each letter). Within this folder are the following:
	Confusion Folder – Images of confusion matrices used in the report

	Input and Targets – Contains the input and target matrices used in the neural network
(Note Input Generator.m will save to Inputs (Letter MAT Data folder), but input was reproduced here for convenience) 
Inputs (Letter MAT Data) – contains processed data that applies feature to raw .wav files, overall input matrix used in the neural network is generated here after running Input Generator.m
	MATLAB Code – Code used in Code and Neural Network video

Papers and Other Files folder contains my project report, all papers used for this project, and other miscellaneous files 
	My paper that I wrote is here called, Final Project Report_Keyboard Inference via Acoustic Signals in both pdf and docx format
Project Videos and Presentations – Contains all videos and presentations 

Random Files for Self Learning folder – This folder can mostly be ignored, just random matlab code or files I used to help me learn different things like relearning how to perform the fourier transform in matlab, experimenting with cross correlation, and etc
