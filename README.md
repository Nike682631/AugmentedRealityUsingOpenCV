# AugmentedRealityUsingOpenCV

In this project I've tried to use Augmented Reality Technology to re-create a small task. 

# What it basically does? #

It uses the target image given by the end-user and superimposes a video on it. Here we are imposing video, but we can imposing any 2d object on it.
We will be using ORB detector to find the keypoints and descriptors for the image. Then we will be finding matches using knn BruteForce Matcher(we
are finding the distance between the camera and the target image, and based on our favourable distance we are continuing our operation). 
This method provides us the good matches to determine if the target was detected or not. Then we are creating the right mask and augment our image
and then video.

# Inspired from: #

1) Abhishek Singh's Super Mario Bro's Recreated as Life size Augmented Reality Game : https://www.youtube.com/watch?v=QN95nNDtxjo
2) Microsift's Hololens : https://www.youtube.com/watch?v=6lxGU66w0NM
3) Google's AR Core : https://www.youtube.com/watch?v=VOVhCTb-1io

Thanks to Murtaza Hassan for his unbelievable efforts.
