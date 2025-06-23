# The-Gaming-Room
Draw It or Lose It is a multiplayer game system designed for The Gaming Room, featuring a scalable, object-oriented architecture built around Singleton logic and entity inheritance. This repository includes the full software design document detailing requirements, constraints, UML diagrams, and platform recommendations for distributed deployment.

Draw It or Lose It – Software Design Document 

Overview 

This repository contains the completed software design document for Draw It or Lose It, a multiplayer game platform created for The Gaming Room. The document demonstrates core software architecture principles, including use of the Singleton design pattern, inheritance, and object-oriented encapsulation. It also outlines platform recommendations, security considerations, and distributed systems architecture to support a scalable and secure game environment. 

 

Submission Information 

This README serves as the final submission for the CS 230 course project. The contents below reflect the design and development process used in creating this document and the system design for The Gaming Room. 

 

Who was the client? What type of software did they want you to design? 

The client was The Gaming Room, a company aiming to expand its portfolio with a new multiplayer game titled Draw It or Lose It. They requested a well-structured software design for a scalable, distributed game system that could manage players, teams, and game sessions reliably. The goal was to ensure stability, clarity, and long-term maintainability across platforms. 

 

What did you do particularly well in developing this documentation? 

I clearly defined the system architecture and object-oriented design using a UML class diagram that emphasized code reusability, consistency, and scalability. The use of Singleton GameService and an Entity base class allowed the structure to be intuitive and clean. I also provided detailed system recommendations for deployment, including platform choices and security practices, which align with modern cloud-based development standards. 

 

What about the process of working through a design document did you find helpful when developing the code? 

Working through the design document helped clarify the relationships between objects before a single line of code was written. It made it easier to enforce consistency and understand how changes in one component might affect other components. Planning for constraints like distributed environments and data integrity up front gave me a solid foundation for building maintainable and testable software. 

 

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it? 

If I could revise one part, I would expand the System Architecture View section. Currently marked as N/A, this section includes diagrams showing API interactions, data flow, or deployment strategy. Adding these elements would further clarify how the design translates into an actual running system and would be useful for both developers and stakeholders. 

 

How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing? 

The user's needs were interpreted through a balance of gameplay experience and backend manageability. Features like automated ID assignment, clear team/player hierarchies, and Singleton-based control reflect the importance of a system that just works—without error or conflict. Understanding the end-user experience is critical because it ensures the software remains intuitive, performs efficiently, and scales smoothly as user demand grows. 

 

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application? 

I approached the design by first modeling the core entities (Game, Team, Player) and identifying shared attributes to consolidate them into a base class (Entity). I applied design patterns like Singleton to manage centralized states and used UML diagrams to visualize relationships. In the future, I will continue to use this pattern-focused, diagram-driven approach and incorporate sequence diagrams and user stories earlier in the process to align technical design with user expectations. 

 

Author 

Justin Turner 

 CS 230 – Southern New Hampshire University 

 Date: 05/23/2025 

 Version: 1.0 
