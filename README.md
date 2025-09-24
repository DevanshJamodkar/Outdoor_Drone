# Outdoor Drone – Drone Swarm Simulation

This project is a **drone swarm simulation system** built using **ArduPilot (ArduCopter)** and the **Skybrush ecosystem**.  
It allows simulating outdoor drone light shows with multiple UAVs, synchronized flight patterns, and real-time visualization.

🚧 **Note:** The project is still in development and may evolve over time.

---

## 🙌 Shoutout & Credits

This project is inspired by and based on the guide:  
👉 [Running a Drone Light Show with ArduCopter and Skybrush (ArduPilot Forum)](https://discuss.ardupilot.org/t/running-a-drone-light-show-with-arducopter-and-skybrush/88595)

Huge thanks to the **ArduPilot team** and **Skybrush developers** for making this possible!  

---

## 📦 Included Submodules

This repository includes the following components as submodules:

- `ap-swarm-launcher` – tool to launch multiple SITL instances for swarm simulation  
- `live` – Skybrush Live (control software for managing the show)  
- `skybrush-server` – backend server for communication  
- `studio-blender` – Skybrush Studio (Blender add-on for designing drone shows)  
- `viewer` – Skybrush Viewer (real-time visualization of the swarm)  

---

## 🚀 Getting Started

### 1. Clone the Repository with Submodules
```bash
git clone --recurse-submodules https://github.com/DevanshJamodkar/Outdoor_Drone.git
cd Outdoor_Drone
```

## If you already cloned without submodules, run:
```bash
git submodule update --init --recursive
```

##  Install Dependencies
Install ArduPilot (with ArduCopter SITL support) → ArduPilot Setup Guide

Install Blender (for Skybrush Studio add-on) → Blender Download

Install Python 3.x and required Python packages for Skybrush tools:
```bash
pip install -r requirements.txt
```

