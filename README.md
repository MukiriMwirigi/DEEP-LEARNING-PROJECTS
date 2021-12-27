PROJECT 1 - AUTOMATIC REVIEW ANALYZER
Building a classifier that labels reviews as positive or negative using text-based features and the linear classifiers that you implemented in the previous section!

The data consists of several reviews, each of which has been labeled with  or , corresponding to a negative or positive review, respectively. The original data has been split into four files:

reviews_train.tsv (4000 examples)
reviews_validation.tsv (500 examples)
reviews_test.tsv (500 examples)


PROJECT 2 - MNIST DIGIT RECOGNITION
Solving the famous digit recognition problem using the MNIST database through different methods including linear and logistic regression, non-linear features, regularization, kernel tricks and Neural Networks.
The MNIST database contains binary images of handwritten digits commonly used to train image processing systems. The digits were collected from among Census Bureau employees and high school students. The database contains 60,000 training digits and 10,000 testing digits, all of which have been size-normalized and centered in a fixed-size image of 28 × 28 pixels. Many methods have been tested with this dataset and in this project, you will get a chance to experiment with the task of classifying these images into the correct digit using some of the methods you have learned so far.


PROJECT 3 - NETFLIX RECOMMENDER SYSTEM 
Building a mixture model for collaborative filtering using a data matrix that contains movie ratings made by users dervived from the larger Netflix database. The matrix is partially filled and the task is to fill the remaining entries.


PROJECT 4 - REINFORCEMENT LEARNING TEXT BASED GAME
For this project you will conduct experiments on a small Home World, which mimic the environment of a typical house.The world consists of a few rooms, and each room contains a representative object that the player can interact with. For instance, the kitchen has an apple that the player can eat. The goal of the player is to finish some quest. An example of a quest given to the player in text is You are hungry now . To complete this quest, the player has to navigate through the house to reach the kitchen and eat the apple. In this game, the room is hidden from the player, who only receives a description of the underlying room. At each step, the player read the text describing the current room and the quest, and respond with some command (e.g., eat apple ). The player then receives some reward that depends on the state and his/her command.

In order to design an autonomous game player, we will employ a reinforcement learning framework to learn command policies using game rewards as feedback. Since the state observable to the player is described in text, we have to choose a mechanism that maps text descriptions into vector representations. A naive approach is to create a map that assigns a unique index for each text description. However, such approach becomes difficult to implement when the number of textual state descriptions are huge. An alternative method is to use a bag-of-words representation derived from the text description. This project requires you to complete the following tasks:

Implement the tabular Q-learning algorithm for a simple setting where each text description is associated with a unique index.

Implement the Q-learning algorithm with linear approximation architecture, using bag-of-words representation for textual state description.

Implement a deep Q-network.

Use your Q-learning algorithms on the Home World game.



Note: This repo also includes code written by the course staff.

Status: Completed
