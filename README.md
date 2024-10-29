# Transcendence by RaphRsl
![Screenshot from 2024-10-29 11-57-52](https://github.com/user-attachments/assets/76a58dc0-4de5-430f-8e26-38dd40c0b682)

## Description

The **Transcendence** project aimed to create a comprehensive **online multiplayer game** platform, making use of **full-stack** web development technologies. As the final project in the core part of École 42’s curriculum, it tested our abilities to work in a team while tackling real-world challenges, from frontend and backend development to implementing cybersecurity and DevOps practices. This project embodied the culmination of our foundational learning and served as a bridge into the more advanced topics of the 42 curriculum.

## Overview of the Project

- **What the Project Is:**
  **Transcendence** was a full-stack web-based gaming platform that required us to implement a secure, scalable, and feature-rich online game environment. It combined game development, user interaction, data management, and advanced security measures.

- **Languages and Technologies:**
  - **Python (Django)** / **Vanilla JavaScript** / **PostgreSQL** / **HTML/CSS** / **ThreeJS** / **Docker** / **Docker Compose**

- **Key Features:**
  - Designed as a **single-page application** (SPA) for improved performance and user experience, allowing instant interactions without full page reloads.
  - Developed using a secure and scalable backend with **Django**.
  - Implemented user authentication with **Two-Factor Authentication (2FA)** and **JWT**.
  - Deployed the entire application using **Docker** containers for consistency and ease of setup.
  - Enabled game modes, including single-player against AI and multiplayer modes.
  - Created dynamic customization options for user experiences.
  - Managed a full-fledged tournament system for competitive play.
  - Designed advanced 3D graphics using ThreeJS to provide an immersive experience.

## Technical Notions and Key Parts

<table>
  <thead>
    <tr>
      <th>Field</th>
      <th>Technology</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="4"><strong>Web</strong></td>
      <td><strong>Django</strong></td>
      <td>Built the backend using Django, which provided a stable framework to develop and maintain the application’s core functionalities. It handled all data processing and interactions.</td>
    </tr>
    <tr>
     <td><strong>Single-Page Application (SPA)</strong></td>
     <td>Designed as a single-page application to provide a smooth and interactive user experience, minimizing load times and enabling instant content updates without full page reloads.</td>
    </tr>
    <tr>
      <td><strong>PostgreSQL</strong></td>
      <td>Implemented the database with PostgreSQL, allowing efficient and scalable data storage for user information, game stats, and tournament records.</td>
    </tr>
    <tr>
      <td><strong>HTML/CSS & Vanilla JavaScript</strong></td>
      <td>Developed the front-end with standard HTML, CSS, and JavaScript, creating a responsive and interactive interface without relying on additional frameworks.</td>
    </tr>
    <tr>
      <td><strong>User Management</strong></td>
      <td><strong>Standard User Management</strong></td>
      <td>Managed users through secure sign-up, sign-in, and profile handling, ensuring a seamless and safe experience for all players.</td>
    </tr>
    <tr>
      <td rowspan="3"><strong>Gameplay</strong></td>
      <td><strong>Game Customization Options</strong></td>
      <td>Designed game customization features, allowing players to personalize their game experiences by adjusting various in-game settings, such as ball speed, racket size, and color choices.</td>
    </tr>
    <tr>
      <td><strong>AI Opponent</strong></td>
      <td>Implemented AI functionality to allow players to play solo against an intelligent opponent, providing a challenging single-player mode.</td>
    </tr>
    <tr>
      <td><strong>Tournament</strong></td>
      <td>Implemented a round-robin tournament system for up to 6 players with custom tiebreak logic, enhancing competitive gameplay.</td>
    </tr>
    <tr>
      <td rowspan="2"><strong>AI-Algo</strong></td>
      <td><strong>AI Opponent</strong></td>
      <td>Developed an AI system to provide a challenging experience for players in a single-player mode.</td>
    </tr>
    <tr>
      <td><strong>User and Game Stats Dashboards</strong></td>
      <td>Developed real-time dashboards displaying player statistics, game performance, and other critical metrics for tracking user progress and engagement.</td>
    </tr>
    <tr>
      <td rowspan="2"><strong>Cybersecurity</strong></td>
      <td><strong>Two-Factor Authentication (2FA)</strong></td>
      <td>Added an extra layer of security by implementing Two-Factor Authentication using the Google Authenticator app, ensuring a secure user experience and protecting sensitive data.</td>
    </tr>
    <tr>
      <td><strong>JWT</strong></td>
      <td>Utilized JWT-based access control to manage user sessions and secure data exchanges within the application.</td>
    </tr>
    <tr>
      <td rowspan="2"><strong>DevOps</strong></td>
      <td><strong>Microservices</strong></td>
      <td>Designed the backend using microservices and RESTful APIs, allowing for independent scaling and easier team collaboration on different application components.</td>
    </tr>
    <tr>
      <td><strong>Docker/Docker Compose</strong></td>
      <td>Used Docker and Docker Compose for consistent deployment across environments, ensuring the application runs smoothly in different setups.</td>
    </tr>
    <tr>
      <td><strong>Graphics</strong></td>
      <td><strong>ThreeJS</strong></td>
      <td>Created immersive 3D game graphics using ThreeJS, enhancing user interaction and making the game more visually appealing.</td>
    </tr>
    <tr>
      <td><strong>Accessibility</strong></td>
      <td><strong>Expanding Browser Compatibility</strong></td>
      <td>Expanded browser compatibility to ensure the game works smoothly across all major browsers, providing a consistent experience regardless of the user’s device.</td>
    </tr>
  </tbody>
</table>


<br>
<div align="center">
  <img src="https://github.com/user-attachments/assets/01c274bd-e7b9-48d2-bf2e-2c08511ee00e" width="500" />
  <img src="https://github.com/user-attachments/assets/fd9db9a8-888b-41ad-a891-c3f8e4c5e830" width="500" />
</div>
<div align="center">
  <img src="https://github.com/user-attachments/assets/8c45f8d5-97c2-444c-b00c-97c9dd13c821" width="500" />
  <img src="https://github.com/user-attachments/assets/271c9b91-7ef7-4eaf-8a1d-11b93e9d64fb" width="500" />
</div>

<hr style="width: 50%; margin: auto;">
<br><br>

*Good luck!* Don’t hesitate to reach out if you have questions or suggestions for improving this README file! Feel free to star the repository if you find it useful and want to support me! ⭐ Sharing it with friends who might be struggling will also make you a hero!

## Author and Contributing

This project was created by RaphRsl as part of my curriculum at École 42 Paris (username rroussel). It was intended for academic purposes only. If you found this project useful, please consider starring the repository to show your support! ⭐

### How to Contribute

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.
