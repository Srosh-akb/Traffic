## Traffic
CS50AI Project 5 - AI to identify which traffic sign appears in an image.

## Instructions
1. Download this repository to your device.
2. Open a terminal or command prompt.
3. Navigate to the directory where you downloaded the repository.
4. Install the requirements usign the following command
```bash
pip3 install -r requirements.txt
```
5. Run the file with Python 3 using the following command
```bash
python traffic.py gtsrb
```
6. Watch the AI process the data for 10 Epochs and evaluate its accuracy after

## Background
One of the largest challenges faced by the development of self-driving cars is computer vision,
the ability to recognise and distinguish different road signs.

This project uses TensorFlow to build a neural network to mimic the way a brain works in image recognition 
and processing. Using TensorFlow, the neural network can be completely customized, allowing for varying hidden layers
and nodes choices that best suit the data. For this problem 1 hidden layer was used with 128 nodes, this yielded an accuracy of 94%. The model can be changed to suit any problem, changing number of nodes or hidden layers can be beneficial to different data types and processing powers.

Image convolution is also used to filter the image pixels into trainable data. Pooling can also help this process by shrinking image size so that the model is able to process the data in time.

The GTSRB dataset (dataset containing thousands of images of 43 different sign types) was used to train the model, providing labelled images that can help give weights to arcs connecting nodes within the neural network.

