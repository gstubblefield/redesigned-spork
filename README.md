Artemis Financial (CS305)

•	Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial was a new company that wanted to make sure they were up to the security standards for their system. The wanted to make sure that their communications were secure and that there data was encrypted.

•	What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
When coming into this I hadn’t had much experience at all with security and found it completely new. I thought that what I did well was using the URL to test different aspects of vulnerabilities to try. Security for a financial institution is required to operate because you are dealing with such sensitive information. Customers don’t want their credit card numbers getting stolen or seen from an attacker and they depend on the institution to keep it safe. When companies can do this overtime, it builds trust with the customers and employees of the company. That trust happens when everything runs smoothly and allows your business to keep advancing.

•	What about the process of working through the vulnerability assessment did you find challenging or helpful?
When working through the vulnerability assessment I found it most challenging to know what aspects to look for or where to look for them. Sometimes the given code base was so simple I didn’t know where a vulnerability may be presenting itself. Another aspect of it was not knowing all the software used like Tomcat. 

•	How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
To increase the layers of security I added in self-signed certificates, encrypted strings, and passed the information securely through to the client/server. When adding in these layers of security I had to determine what algorithms to use. By doing research and seeing what the industry standards were I was able to gain further information of how the data is encrypted. In the future when determining vulnerabilities I will be better at knowing where the vulnerability lies and better at finding ways to fix it. Determining the mitigation technique to fix it may require an update, restart, or just writing the code differently. Knowing when it is a false-positive comes over time and more understanding to which I will further my knowledge next term.

•	How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
The make sure the code is functional and secure I did different tests and assessments. I did a dependency check before working with the code to see what was going wrong. Then after I refactored the code, I ran another dependency check. After reviewing this report, I could see if I created any new vulnerabilities and have a better understanding of the vulnerabilities that were found. I would also do code reviews with manual tests with the URL and checking to make sure known vulnerabilities were not coming up. 

•	What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
Some techniques I tried was testing out different implementations of SHA-256 and it helped me get a better understanding on what I was doing with the string. Getting multiple points of view on a subject can help tremendously since everyone sees things different. 

•	Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
From this I would want them to see my Vulnerability Assessment Report that shows I can take a code base and identify the different aspects of security and how to defend against them. I was able to figure out the clients needs and write a report on what to do and doing some various testing. This would showcase knowledge of security and that I know how to find vulnerabilities in different software. 

DriverPass (CS255)

•	Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?
This system design was for the company DriverPass and the owner Liam. The system will allow them to create a web browser ran application that will streamline the third party training to student drivers. DriverPass saw a void in the market in their area in third party student trainings so they wanted a system that will allow student to purchase packages and schedule lessons, study, and take tests. They wanted a system for the students and the drivers that will be training the students in the vehicles. 

•	What did you do particularly well?
I thought I captured a good way to transition the system from just the design to development. The system focuses on a database and calendar. By doing that any information a user needs can be accessed through that when allowed with correct authorization.  

•	If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
The one part I would like to go back, and change would be the initial requirements in the business requirements document. When I was making the requirements, I was thinking a much more business level and not system level. I would like to make each requirement more tightly defined by actions like user stories. It was the first part and I was just trying to think of ways to build off what the customer said and should have focused more on the concrete design of what Liam wanted. 

•	How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?
To figure out what Liam wanted out of the DriverPass system I had an interview with him and got to ask a lot of questions and get his answers and vision of the system. It is crucial to understand what a client wants out of the system. This is because they have a vision and through good communication is the best way for a systems analyst to build that vision. For this system I thought Liam wanted a simple system for everyone to use and he just wants to see how everything happened through the database. 

•	How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?
Before this system when I had to design software I tried to get out there and see what I could come up with in the code and tweak aspects after creating them, but now I have a total different view. Now I feel its best to workout the use cases and find all the aspects that would need to be included in that. This helped me see in the DriverPass system that if I were to design it that I would just need to focus on a few objects and a database to store them all. The best strategy is taking the use cases and seeing trying to build class diagram. Doing several iterations may be need when you see other ways or methods you can implore. Overall I was grateful for the strategies learned while designing different aspects of the system. 


// Project Three Design Document

 In this software design document, I was charged with the task of creating the software and system design for Draw it or Lose it by the Gaming Room. They wanted a game that could only have a single instance of the game service with multiple games running cross platform at the same time. Each game would consist of teams with multiple players on each team. I thought I used inheritance and data storage for each game instance well. When a new game is created it uses a RESTful API and how the data would be sent to after requests are made. Having the game make less requests was key to ensuring that using cloud-based servers would be the most cost effective. One part of the design document I would revise would be the RESTful API and how the cross platform is designed since I did not get the chance to make the code run on my system for some reason. My overall approach for this design document was to be able to scale and still be cost effective. 
 
 // ZooJava
 
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
