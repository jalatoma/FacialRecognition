# General Engineering Facial Recognition
In this project, we wrote a set of user-defined functions in order to perform a very basic implementation of face recognition. 
Face recognition is a very active and popular research topic that is used for a range of different fields from application development to security systems. Each face recognition system requires a face database. 
(Otherwise it would not know whom to recognize!) As the face database in this project, we will use the faces of 100 National Basketball Association (NBA) players.

In the database, we have access to 100 RGB images (color images) of 100 different players. The size of each one of the R, G and B channels in each image is m×n = M. We need to read these images, convert them to grayscale, vectorize (see Fig. 2) them and store them in the columns of a database matrix D of size M × 100. In the database, each column should contain a vectorized image of m × n = M pixels and there should be 100 such columns. (because there are 100 players) Furthermore, we also need a label vector p of size 100 × 1 that holds the name of the k-th player at its k-th entry, where k = 1...100.

Since we know the location of each player in the p vector, the easiest way to perform face recognition would be to reorder the columns of the database D such that the vectorized image of the k-th player is at the k-th column of the D matrix. Then, when we have a query image, we can find the column of the D matrix that holds the vectorized image which is most similar to our query image and then identify the player as player-k with name Name-k.

**Worked on this project with a partner in Fall of 2019. The .m file uploaded is our coded work.**

All work was done in MatLab's 2019 version released in September 2019. 

Explnation of the two files:
 - LabProject.m : All the MatLab code we wrote for the basic facial recognition software
 - LabProject.html : When downloaded and opened, presents the code and images we used in a more user-friendly, organized way to better understand our findings. 
