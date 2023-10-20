# CS370-Current-Emerging-Trends


# Briefly explain the work that you did on this project:

  -What code were you given?
      The code for the project I worked on was for an AI model to navigate a maze and find treasure at the end of the maze. This model used reinfocement learning in order to grow and find the treasure at the end of the maze more efficiently. For this project, we were given three files: one ipynb file and two python files. The first python file, which was called TreasureMaze.py held code that was used to setup the maze that was used as the environment for the AI model to navigate. There were multiple functions in this file that were used to create the maze, reset the maze, return the game status, and draw a model of the maze. These functions were mostly related to the ennvironment setup. The TreasureMaze.py file also held functions that were used to update the state for the AI model agent, give rewards to the AI model agent, determine the valid actions for the agent, observe the state, and track the total reward for the agent. This code from this file was used in the ipynb file to setup the test environment. The second python file was called GameExperience.py. This file was used to provide functionalities that allowed the AI model/agent to store the experiences from the numerous tests it did in the maze environment. Essentially, this class provided functions that would: record data related to the AI agent's episodes in memory, predict the next action for the AI agent, and return said experience data when called. The last portion of code given to me was the ipynb file. This notebook file integrated both of the python files I mentioned prior in order to setup the AI model, as well as the maze environment. In this notebook, the valid actions for a user were defined, the maze was built using the TreasureMaze file/class, the neural network model was built, a portion of the reinforcement learning algorithm was provided, and then tests were run using the neural network model.

  -What code did you create yourself?
      For the project, the only code I had to create was a portion of the Q-Training algorithm that acted as the reinforcement learning algorithm being used by the neural network. The portion of code not given was the part that would have the agent run through multiple games, gain experiences, record said experiences, and learn from said experiences in the next iteration. Basically, I had to build the portion of the Q-Learning algorithm that forced the AI agent to explore and learn. Eventually, the code would tell the agent to start using its knowledge of the environment and experiences to solve the maze more efficiently. So, in review, I had to create a loop that would run in the Q-Learning algorithm that forced the agent to continuously play the maze game and learn.

# Connect your learning from throughout this course to the larger field of computer science:

  -What do computer scientists do and why does it matter?


  -How do I approach a problem as a computer scientist?


  -What are my ethical responsibilities to the end user and the organization?
