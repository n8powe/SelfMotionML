# SelfMotionML

This repository will contain the codebase for a ML model of estimating self-motion parameters (See paper linked below for what self-motion parameters are taken to mean).

## Required:

Unity Version 2021.3.16f1 (download Unity Hub and then download this editor version)

Once Unity is installed, open this project. It should use the meta data to build everything required.

Go to Window at the top, then package manager, and install ML Agents. If that does not work, use the first link below, download from source and then import into your project. (To import package go to package manager, click the + sign, choose from disk, and then find the .json file in the packages directory).

## More

This link (https://www.biorxiv.org/content/10.1101/2021.07.09.451701v3) is the inspiration for the study.

The current goal is to take their NN structure and train it with different stimuli and with different methods.

1) Train it using human data during walking

2) Use deep RL methods to train an agent to move towards a goal location and concurrently estimate the parameters of its own self motion.

Useful links:

https://github.com/Unity-Technologies/ml-agents

https://github.com/Unity-Technologies/ml-agents/blob/develop/docs/Python-LLAPI.md

https://github.com/Unity-Technologies/ml-agents/tree/develop/docs

https://github.com/Unity-Technologies/ml-agents/blob/develop/docs/Learning-Environment-Create-New.md
