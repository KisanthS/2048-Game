2048 Game Deployment Using Docker

Project Overview

This project demonstrates how to deploy the 2048 Game using Docker. The setup includes pulling the 2048 game repository, building a Docker image, and running the container.

Prerequisites

Docker installed on your system (for Windows, Docker Desktop is required)

Git installed

Steps to Deploy the 2048 Game

1. Clone the Repository

git clone https://github.com/KisanthS/2048-Game.git
cd 2048-Game

2. Load the Docker Image

If you already have the Docker image tar file:

docker load -i 2048-game.tar

3. Run the Docker Container

docker run -d --name 2048-game -p 80:80 2048-game

4. Access the Game

Open your browser and go to:

http://localhost:80

You should see the 2048 game running!

Troubleshooting

Ensure Docker is running on your system.

If you encounter errors, try running commands with admin/root permissions
