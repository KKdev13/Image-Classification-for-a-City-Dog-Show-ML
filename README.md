Description:
Your city is hosting a citywide dog show and you have volunteered to help the organizing committee with contestant registration. Every participant that registers must submit an image of their dog along with biographical information about their dog. The registration system tags the images based upon the biographical information.

Some people are planning on registering pets that aren’t actual dogs.


Your Tasks:
.Using your Python skills, you will determine which image classification algorithm works the "best" on classifying images as "dogs" or "not dogs".

.Determine how well the "best" classification algorithm works on correctly identifying a dog's breed. If you are confused by the term image classifier look at it simply as a tool that has an input and an output. The Input is an image. The output determines what the image depicts. (for example, a dog). Be mindful of the fact that image classifiers do not always categorize the images correctly.

.Time how long each algorithm takes to solve the classification problem. With computational tasks, there is often a trade-off between accuracy and runtime. The more accurate an algorithm, the higher the likelihood that it will take more time to run and use more computational resources to run.

Important Notes:
For this image classification task, you will be using an image classification application using a deep learning model called a convolutional neural network (often abbreviated as CNN). CNNs work particularly well for detecting features in images like colors, textures, and edges; then using these features to identify objects in the images. You'll use a CNN that has already learned the features from a giant dataset of 1.2 million images called ImageNet. There are different types of CNNs that have different structures (architectures) that work better or worse depending on your criteria. With this project, you'll explore the three different architectures (AlexNet, VGG, and ResNet) and determine which is best for your application.

Remember that certain breeds of dogs look very similar. The more images of two similar-looking dog breeds that the algorithm has learned from, the more likely the algorithm will be able to distinguish between those two breeds.

Principal Objectives
1.Correctly identify which pet images are of dogs (even if the breed is misclassified) and which pet images aren't of dogs.

2.Correctly classify the breed of dog, for the images that are of dogs.

3.Determine which CNN model architecture (ResNet, AlexNet, or VGG), "best" achieve objectives 1 and 2.

4.Consider the time resources required to best achieve objectives 1 and 2, and determine if an alternative solution would have given a "good enough" result, given the amount of time each of the algorithms takes to run.

