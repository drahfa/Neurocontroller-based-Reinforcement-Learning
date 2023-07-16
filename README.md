# Neurocontroller-Based Reinforcement Learning (2023 Readme)
Notes: This tutorial is forked from the work of Kip Parker where his excellent write-up can be found here: https://towardsdatascience.com/building-a-neural-network-framework-in-c-16ef56ce1fef
Kip has put together an example and I hope I can expand this further in the teaching lessons.

## What is a Neurocontroller?

A neurocontroller is a type of controller in control systems that utilizes a neural network to manage the behavior of the system. Essentially, it's a control system whose decision-making structure is modeled after biological neural networks. The neurocontroller leverages the neural network's ability to learn from data, adapt to new scenarios, and handle complex, non-linear systems. It applies these capabilities to regulate and control dynamic systems, even in cases where the system's mathematical model is unknown or complex, making it highly valuable in a variety of real-world applications such as robotics, process control, and autonomous vehicles.

## What is Reinforcement Learning?

Reinforcement learning is a form of machine learning where an agent learns to make decisions by interacting with an environment. This methodology falls somewhere between supervised and unsupervised learning. Unlike supervised learning where models learn from labeled examples, or unsupervised learning where models discern patterns in unlabeled data, reinforcement learning agents optimize actions through a system of rewards and penalties gained from trial-and-error.

Viewing reinforcement learning in the context of unsupervised learning, one could assert that the agent learns to comprehend the environment and make optimal decisions without explicit supervision. However, it's important to note that the agent does learn from feedback, although more indirectly and delayed than in traditional supervised learning. Thus, reinforcement learning can be perceived as a type of unsupervised learning with unique decision-making and optimization elements, allowing an agent to interact with an environment based on the feedback received.



--------------------------------------------------------------------------------------
# C# neural network (2020 Readme)

Neural network capable of forward passing and mutation driven learning

##  Dependiencies

* Unity

[Install unity](https://unity3d.com/get-unity/download). 

## Usage

The files will appear you your assets

With unity installed you can go to assets/scene/environment.unity and open it

If you dont want to wait for the model to train. you can load the pretrained model txt files from with in manager InitNetworks function

## Process of creation and explanation of neural networks

I wrote a medium article explaining in simple terms how neural networks work, this can be found at: https://towardsdatascience.com/building-a-neural-network-framework-in-c-16ef56ce1fef
