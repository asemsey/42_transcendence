# ft_transcendence

`ft_transcendence` is a full-stack web application developed as the final project of the 42 curriculum. It is a real-time multiplayer Pong game built with modern web technologies, offering features such as user authentication (including OAuth), friend management, match history, and user profiles. The application emphasizes real-time communication, responsive design, and security best practices. The backend and frontend were developed separately and communicate via a REST API.

## Features

- **User Authentication**:
  - Login / Sign up
  - OAuth integration (Google login)
- **Real-time Pong Game**:
  - Play against other users or bots
- **Friends System**:
  - Send/accept friend requests
- **Profile Management**:
  - Profile picture uploads
  - Match history tracking
  - Stats display (wins, losses, etc.)
  - database SQLite3
- **Security**:
  - Token-based authentication (JWTs)
  - Input validation and sanitization
- **Responsive Design**:
  - Mobile and desktop support for a seamless experience across devices.
  - Frontend written with Typescript and TailwindCSS

## Installation

To run the project locally:

1. Clone the repository:

    ```bash
    git clone https://github.com/asemsey/42_transcendence.git
    cd 42_transcendence
    ```

2. Configure environment variables:

edit the .env and .env.backend files

3. Build and run the project using the Makefile:

    ```bash
    make
    (to run the entire app)
    make app
    (to run just the webapp without devops)
    make elk
    (to run just the devops)
    ```

4. Access the frontend in your browser:

The app will typically run on `localhost:3000`, unless you configured another port in .env.backend.

