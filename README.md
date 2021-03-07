# StudenTeacher
*"Tell me and I will forget. Teach me and I remember. Ivolve me and I learn"* - Benjamin Franklin

StudenTeacher is a web application built to give students the ability to be involved in their learning, **even during a pandemic**. Using WebRTC technology, students are able to join small meeting groups to teach each other concepts that they learned in class. The application was designed and developed to be easy to use and accesible to all users regardless of technical knowledge or technology available to them. As long as the user has an internet connection, they can use this application to get involved in their learning. 

# Motivation For This Software:
It's my strong belief that education is a right to everyone, this software aims to make it easier, and more enjoyable for people to get involved and truly learn from school. That's what drove me to build this software as a web application, because the web can be accessed by any device (even a fridge), so there are no restrictions on who can use this software. The UI is minimal, simple and easy to navigate allowing non-technical users to easily understand and use the software.

# Technical Aspect:
I used Express for my server structure and API, MySQL (+ sequelize as an ORM) as my DB, Socket.io to send messages and communicate information for p2p connections, Peer JS for the actual p2p connections and for authentication I used Express sessions and JWT + passport JS


