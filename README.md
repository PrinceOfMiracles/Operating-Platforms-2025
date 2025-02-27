# Operating-Platforms-2025

**Project Summary: The Gaming Room & Software Requirements**
  The Gaming Room is a client that sought to expand their existing game, Draw It or Lose It, from a mobile-only Android application to a multi-platform, web-based solution. The goal was to design a scalable distributed system that could support thousands of concurrent users, maintain secure authentication, and optimize storage and memory management for efficient performance. The software needed to be compatible with major web browsers (Chrome, Edge, Firefox, Safari) on Windows, macOS, Linux, and mobile devices, while integrating cloud-based infrastructure for scalability.

**Strengths in Developing the Documentation**
  One of my strongest areas in developing the software design document was evaluating different operating platforms and recommending the best environment for deployment. I carefully considered server hosting options, security protocols, and storage solutions, ensuring that the proposed system would be efficient, secure, and cost-effective. Additionally, I clearly outlined client-server architecture, memory management strategies, and distributed networking considerations, which helped create a well-rounded and detailed proposal.

**  How the Design Document Helped in Development**
  Working through the design document before coding was extremely helpful because it provided a clear structure for the system architecture and technical requirements. It allowed me to define key constraints, such as scalability and security, early on, preventing potential issues later in development. Breaking down server-side and client-side requirements also made it easier to determine which tools and frameworks would be best suited for implementation.

**Areas for Improvement**
  If I were to revise one part of the document, I would refine the security implementation details, especially how authentication and encryption methods are applied across different platforms. Adding more depth on OAuth 2.0 token management, API rate limiting, and intrusion detection systems would make the proposal even stronger. Another improvement would be expanding on cost comparisons for different cloud storage solutions, ensuring that budget considerations are well documented.

**User Needs & Implementation**
  Understanding user needs was central to the software design. Draw It or Lose It required real-time gameplay updates, meaning that low-latency server-client communication was crucial. By implementing REST APIs for authentication and WebSockets for game interactions, the design addressed performance concerns while keeping the user experience smooth. Security measures, such as SSL encryption and role-based access control (RBAC), were also implemented to protect user data. Considering user needs is vital because a well-designed system improves usability, engagement, and trust in the application.

**Approach to Software Design & Future Strategies**
For this project, I approached software design by following agile principles, breaking down requirements into modular, testable components. Using object-oriented programming (OOP) principles like abstraction, encapsulation, and polymorphism, I ensured the system could be expanded easily in the future. Moving forward, I would incorporate more DevOps strategies, such as automated testing and CI/CD pipelines, to streamline deployment and testing. Additionally, leveraging Infrastructure as Code (IaC) with Terraform or AWS CloudFormation could improve scalability and system maintenance.

