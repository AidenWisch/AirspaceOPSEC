# AirspaceOPSEC
Fine tuning mobile-net v3 large on kaggle skyborne objects dataset runnable on raspberry pi 5 8gb with 1080p webcam. Using bounding box object detection.
Project Idea - Airspace OPSEC

Goal - 
Fine tune a neural network to identify planes, birds, drones, or helicopters.

Website - 
https://www.kaggle.com/datasets/arminajdehnia/skyborne-objects-dataset/data

Description - 
Fine tuning an existing AI model to run both on the cluster and raspberry pi with limited resources in order to detect 4 main objects in the sky. The objects are birds, planes, drones and helicopters. We would compare the performance between the raspberry pi and the cluster. If time permits we plan on testing our experiment in real life near an airport. With this model, it would help determine if the flying object near the airport is allowed to fly or not allowed to fly. For the dataset being used, we are going to use the dataset provided by the link. It offers a bunch of images of flying birds, planes, helicopters, and most importantly drones which will be the most important to get right considering the scope of airport security. We will use MobileNet-V3-Large, a small lightweight CNN that is able to run on mobile devices. MobileNet-V3-Large has roughly 5.47 million parameters and is roughly 20.9MB in size. Using bounding box object detection.

Assignments - 
Mackler-Training/finetuning
Aiden-hardware/testing
(Subject to change)
