# Gesture-Recognition

### Objective
The aim of the project is to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote.
1) Thumbs up:  Increase the volume
2) Thumbs down: Decrease the volume
3) Left swipe: 'Jump' backwards 10 seconds
4) Right swipe: 'Jump' forward 10 seconds  
5) Stop: Pause the movie


### Data Understanding
1) Each video is a sequence of 30 frames (or images) which can be  categorised into one of the five classes.
2) Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images)
3) The data is in a zip file which contains 'train' and a 'val' folder with two CSV files for the two folders. 
4) These folders are in turn divided into subfolders where each subfolder represents a video of a particular gesture.
5) All images in a particular video subfolder have the same dimensions but different videos may have different dimensions. Specifically, videos have two types of dimensions - either 360x360 or 120x160

Dataset Link : https://drive.google.com/uc?id=1ehyrYBQ5rbQQe6yL4XbLWe3FMvuVUGiL


### Model Building 
The below mentioned are the 2 architectures used in the project:-
1) CNN + RNN architecture
2) 3D convolutional network
