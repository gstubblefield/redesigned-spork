# redesigned-spork
// Project Three Design Document
 In this software design document, I was charged with the task of creating the software and system design for Draw it or Lose it by the Gaming Room. They wanted a game that could only have a single instance of the game service with multiple games running cross platform at the same time. Each game would consist of teams with multiple players on each team. I thought I used inheritance and data storage for each game instance well. When a new game is created it uses a RESTful API and how the data would be sent to after requests are made. Having the game make less requests was key to ensuring that using cloud-based servers would be the most cost effective. One part of the design document I would revise would be the RESTful API and how the cross platform is designed since I did not get the chance to make the code run on my system for some reason. My overall approach for this design document was to be able to scale and still be cost effective. 
 
 //ZooJava
This project I built a repository of the animals at the zoo. It holds all the animals in a vector 
and saves all the animals to a file if prompted that can later be used to load in the data if need 
be. I thought I made it user friendly and operates without error quick and efficiently. While I 
really like where the project is the system can be advanced with weights, notes, sex, and other 
facts about animals. I could add these into the animal class so it would be inherited to all the 
animals. I did not have any security features since I haven’t learned that yet. One part of the 
code I did have trouble in was reading in from a file. The reason I had problems was a do 
while loop wasn’t changing the bool properly and would loop back around and add in the 
same data as las loop since the index didn’t change. I was able to fix this by clearing the  
holder data after it was added to the vector. This project was a great learning project and a lot 
of the skills learned will transfer to future projects. Reading and writing to a file is something 
that will have to be done and I think I can do it pretty well. Also in this project I learned to 
use two different languages within the same program. I made this program readable with good 4
spacing and comments. There wasn’t much duplicate code so it was also maintainable and 
adaptable with a very minimal main function. 
