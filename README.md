# **Project Summary**
This project is a game developed for the game studio, The Gaming Room. This studio was looking to a web-based version of their game, Draw It or Lose It. This game renders images from a large library of stock drawings as clues and the players need to guess what the image is within 30 seconds. Each game consists of four rounds of playtime, lasting one minute each. If the team does not guess the puzzle before the time expires, the remaining teams will have an opportunity to offer one guess each to solve the puzzle with a 15-second time limit.

The following software requirements were met for the application:
- Each game has the ability to have one or more teams involved
- Each team has multiple players assigned to it
- Game and team names are unique to allow users to the whether the name is in use when choosing a team
- Only once instance of the game can exist in memory at any given time

The purpose of this design document is to ensure that all developers have a shared understanding of the program's purpose, requirements, and design constraints. When working on the development of the application, this document helped organize and prioritize features that needed to be implemented. It provided a strong reference to support a scalable code base that is also maintainable.

This document allowed Creative Technology Solutions to consider all of the business requirements The Gaming Room has and present the proposal in a coherent display that is understandable to all audiences. Here, we were able to effectively analyze the clients existing infrastructure to create the best possible solution to fit their business needs. The three primary requirements we highlighted to ensure were cross-platform compatibility, reduced costs, and maintainability. 

When finding an architecture to use for this application, we wanted to find one that would provide the strongest foundation to satisfy the business requirements. We chose a cloud-based architecture because it touches upon all three of these requirements. Having a singular code base to host a web-based application removes the need for redundant code to support platform-specific native clients. Having less code to maintain inherently makes the application more maintainable and scalable. Since The Gaming Room already has existing infrastructure, deploying a cloud-based web application would require minimal up-front costs to the client. 
