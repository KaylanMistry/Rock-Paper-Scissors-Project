# Rock-Paper-Scissors-Project
Within this repository is the code I used to create a Rock, Paper, Scissors game using Python.

Milestone 1:

Firstly, I needed to create classes to allow the camera to recognise the images I make when I show each sign.
Using the ‘Teachable Machine’ website, I created a model with four different classes – Rock, Paper, Scissors and Nothing.  
Following this I downloaded the model from the Tensor-Flow tab and the label file to observe what each class corresponded to.

Milestone 2:

Succeeding understanding what each class represented, I created a new conda environment and installed the necessary requirements – opencv, tensorflow, ipykernel and pip.
To ensure the model worked well, I ran this locally and confirmed the labels were correctly named for the model.
Afterwards, as ‘while’ loops and ‘if’ statements were new to me, I spent a considerable amount of time understanding and exploring what I could do with them.

Milestone 3:

For the game to operate I needed to create a function to store the user’s choice – using the teachable machine model. 
Next, I needed to generate a random choice for the computer and store this. 
Using ‘if’, ‘elif’ and ‘else’ statements, I built a script to choose a winner between the computer’s choice and user’s choice; using the classic rules of Rock, Paper, Scissors.
To start the game, I added a start game key where the user had to press the ‘a’ key to begin.
