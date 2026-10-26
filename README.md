# CS 230 Portfolio Reflection: The Gaming Room

## Client and Requirements

The client is The Gaming Room and the requirements come from their need to build an instance of their Android game, Draw It Or Lose It, on multiple platforms. The game is a multiplayer guessing game where the goal is to identify a puzzle as it is gradually revealed as an image. The client needed a web application to manage multiple games, teams, and players and allow for unique naming while keeping consistency in the data.

The design comprised of client-server architecture, cross-platform, security, storage, memory management, and network communication. I recommended the use of Linux servers for the web application as Linux is a reliable, scalable, and cost effective option with Java web services. Other clients, be it web or mobile, can communicate to the Linux server using REST APIs.

## Strengths in Documentation

I compared the game's requirements with the various platforms and came up with a shared server to support multiple players and platforms without having to create multiple server-side applications for the web application. Additionally, I examined security and storage by comparing object storage and relational databases. I also brought in web-based clients instead of choosing a platform because it was familiar to me.

I also integrated security features according to the recommendations. This included features like authentication and authorization, as well as use of HTTPS, protecting credentials, and least privilege. In the prototype, I added basic authentication to restrict access to game-user resources and administrative functions using role-based restrictions on the REST endpoints.

## Helpful Parts of the Design Process

Creating the design document before coding helped me to define the application requirements, components and users, and identify the constraints. The UML class diagram helped with organizing the relationships among games, teams and players. The client-server design helped to figure out what should be done on the server and what should be done on the client.

A platform may be cheap and easy to develop for and scale, but may create security, licensing, hardware and administrative issues.

## Revision Opportunity

I would expand the database and deployment sections if I revised this document. For the database, I would create a detailed data model which includes users, teams, games, rounds, images, scores and audit records. For deployment, I would show client devices, the application servers, the database, object storage, and monitoring services.

I converted the goals for the Gaming Room into use cases and user requirements for development. These include creating and managing games, teams, players, pictures, and user access. There are other needs including accessibility, security, availability, performance, and data consistency. Understanding user requirements will help achieve the game loading quickly, secure user data, give users the flexibility of using the system on the device of their choice, and ensure data is consistent.

Moving forward, I will come up with functional and non-functional requirements, use case diagrams, sequence and collaboration diagrams, interaction and architecture diagrams, data models, and integration diagrams, and other diagrams as needed, to design software before writing a single line of code. I will create a small prototype to validate high risk and uncertain areas such as authentication, and communicate with the server, and check data persistence. I will perform iterative testing and user story mapping. I will design and modify the software based on user feedback.
