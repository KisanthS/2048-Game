🎮 2048 Game Deployment Using Docker
Welcome to the 2048 Game repository! This guide will walk you through deploying the 2048 game using Docker.

🚀 Prerequisites
Ensure you have the following installed on your system:

Docker

Git

🏗️ Steps to Deploy the 2048 Game
Step 1: Clone the Repository
bash
Copy
Edit
git clone https://github.com/KisanthS/2048-Game.git
cd 2048-Game
Step 2: Build the Docker Image
bash
Copy
Edit
docker build -t 2048-game .
Step 3: Run the Docker Container
bash
Copy
Edit
docker run -d --name 2048-game -p 80:80 2048-game
Step 4: Access the Game
Open your browser and go to:
👉 http://localhost

💡 Troubleshooting
Ensure Docker is running before executing commands.

Check the container logs if the game doesn't load:

bash
Copy
Edit
docker logs 2048-game
🎉 Enjoy the Game!
Dive into the addictive 2048 game and have fun!

