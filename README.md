# 🎮 **2048 Game - Docker Deployment**

## 📜 **Project Description**

Experience the classic **2048 game** effortlessly using Docker! This project runs the game on an **Nginx server** within a container, offering a seamless deployment experience.

---

## 🛠 **Prerequisites**

Ensure you have the following installed:

- ✅ Docker (latest version)
- ✅ Git

---

## 🚀 **Getting Started**

Follow these steps to **clone, run, stop, and remove** the container:

### **Step 1: Clone the Repository**

```bash
git clone https://github.com/KisanthS/2048-Game.git
cd 2048-Game
```

### **Step 2: Load the Docker Image (if .tar file is available)**

```bash
docker load -i 2048-game.tar
```

### **Step 3: Run the Container**

```bash
docker run -d --name 2048-game -p 80:80 2048-game
```

### **Step 4: Access the Game**

🌐 Open your browser and visit:
👉 [http://localhost](http://localhost)

---

## 🛑 **Stop and Remove the Container**

### **To Stop the Container:**

```bash
docker stop 2048-game
```

### **To Remove the Container:**

```bash
docker rm 2048-game
```

---

## 💡 **Troubleshooting**

- Ensure Docker is **running**.
- Check for **port conflicts** on port 80.
- Restart Docker if needed.
- On Linux, use `sudo` if permission issues occur.

---
