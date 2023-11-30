+++
title = "YoshAI"
date = "2023-10-31T21:04:24-07:00"
author = false
authorTwitter = false #do not include @
cover = ""
tags = ["PyTorch", "Python"]
keywords = []
description = "Imitation learning applied to Mario Kart Wii"
showFullContent = false
readingTime = false
hideComments = false
color = "blue" #color from the theme settings
sourceCode = "https://github.com/aaronjenson/yoshai"
+++


YoshAI is a project that aims to create an AI that can play Mario Kart Wii at least as effectively as a human. It uses the Dolphin emulator as a simulation platform. At a basic level, YoshAI starts dolphin, finds the window displaying the game, and uses the pixels of the window to predict the best controls to send to dolphin. In collect mode, a user uses a gamepad to control the character and YoshAI saves the images of the game and user inputs as data to be used for training. Train mode uses behavior cloning to train a convolutional neural network to copy the user's inputs. Run mode uses the trained model to play Mario Kart. Dagger mode [TODO]

