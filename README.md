# 2048 Game - Docker Deployment

## 📜 Project Description

This project demonstrates how to run the popular 2048 game using Docker. The game runs on an Nginx server containerized using Docker, providing a seamless deployment experience.

---

## 🛠 Prerequisites

Ensure you have the following installed on your system:

- Docker (latest version)
- Git

---

## 🚀 Getting Started

Follow these steps to clone the repository, build, and run the container:

### Step 1: Clone the Repository

```bash
git clone https://github.com/KisanthS/2048-Game.git
cd 2048-Game
```

### Step 2: Load the Docker Image (If .tar File is Available)

```bash
docker load -i 2048-game.tar
```

### Step 3: Run the Container

```bash
docker run -d --name 2048-game -p 80:80 2048-game
```

### Step 4: Access the Game

- Open a browser and go to: [http://localhost](http://localhost)

---

## 💡 Troubleshooting

- Ensure Docker is running.
- Check for port conflicts on port 80.
- Restart Docker if necessary.
- If using Linux, run Docker commands with `sudo` if permission issues occur.

---
