# Capturing-Screen-Time

Using Deep Learning to Calculate the Screen Time of Actors in any Video.
A model that automatically identified specific people in a given video at a particular time interval.

Our challenge here is to calculate the screen time of both Tom and Jerry from a given video. Let me first summarize the steps we will follow in this article to crack this problem:

1. Import and read the video, extract frames from it, and save them as images(sample Tom and jerry videos)
2. Label a few images for training the model (Done in mapping.csv file).
3. Build our model on training data.
4. Make predictions for the remaining images.
5. Calculate the screen time of both TOM and JERRY.
