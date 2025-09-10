# ROS-2-Mobile-Robot-URDF-Simulation
Internship Task 03: Autonomous Mobile Robot modeled in ROS 2 using URDF/Xacro, TF2 frames, RViz, and Gazebo.

---

## 📥 Setup

### 1. Download the Workspace

* Click the Code button in this repository.
* Select **Download ZIP**.
* Extract the ZIP file into your desired directory.

# 🔽 How to Run

### 2. Open a Terminal

Navigate into the extracted workspace folder:

```bash
cd amr_ws
```

### 3. Build the Workspace

```bash
colcon build
source install/setup.bash
```


### 4 🖥️  – Visualize in RViz

```bash
ros2 launch amr_description display.launch.py
```


### 5 🕹️ – Run in Gazebo and Control Robot

**Terminal 1 – Launch robot in Gazebo**

```bash
cd ~/ros2_ws
colcon build
source install/setup.bash
ros2 launch amr_description gazebo.launch.py
```


👤 Author

Suman Das Adhikary
📧 Email: sumandasadhikary457@gmail.com

For any doubts or queries, feel free to reach out.

📜 License

This project is licensed under the MIT License – you are free to use, modify, and distribute it with proper attribution.
