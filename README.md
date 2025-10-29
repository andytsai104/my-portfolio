# Chih-Hao (Andy) Tsai — M.S. in Robotics & Autonomous Systems @ASU

> Autonomous Vehicle Systems • Robotics • Machine Learning (DL & RL) • Perception (Computer Vision)

[LinkedIn](https://www.linkedin.com/in/chih-hao-tsai/) · [Email](ctsai67@asu.edu) · [GitHub](https://github.com/andytsai104) · [Resume (PDF)](./Resume_CT.pdf)

---

## About Me
I’m a graduate student in **Robotics and Autonomous Systems** at **Arizona State University**, expected to graduate in **May 2026**. I’m passionate about **robotics, motion planning, and intelligent systems**, and enjoy building solutions that combine control, perception, and learning.

With a background in **mechanical and electrical engineering**, I’ve led and contributed to projects involving **robotic arm control**, **autonomous vehicles**, and **image-based path planning**. I also have experience training **deep learning models** for **image generation**, **image segmentation**, **pedestrian trajectory prediction**, etc. My technical expertise includes **Python (PyTorch, TensorFlow, OpenCV)**, **ROS 2**, **Linux**, **MATLAB**, **Simulink**, **C/C++**, **SolidWorks**, **Deep Learning**, and **Reinforcement Learning**.

I’m especially interested in how learning-based systems can enhance robot autonomy — enabling machines to move, perceive, and make decisions safely in complex environments.

---

## Technical Highlights

| Category | Skills & Tools | Proficiency / Focus |
|:----------|:---------------|:--------------------|
| **Programming** | Python (PyTorch, TensorFlow, OpenCV), MATLAB, Bash, C/C++ | Python – Advanced<br>MATLAB – Intermediate<br>Bash – Intermediate<br>C/C++ – Entry |
| **Robotics & Systems** | ROS 2 (RViz, Gazebo, MoveIt), Path Planning & Motion Control, PID Control, Arduino | ROS 2 – Intermediate<br>Planning/Control – Intermediate<br>PID/Arduino – Entry |
| **Tools** | Linux, Git, Simulink, SolidWorks | Linux – Intermediate<br>Git – Intermediate<br>Simulink – Intermediate<br>SolidWorks – Entry |
| **Simulations**| RViz, Gazebo, Carla | RViz - Intermediate<br>Gazebo - ntermediate<br>Carla - Entry|
| **Machine Learning** | Deep Learning (CNN, GAN, ViT), Reinforcement Learning (TD3, SAC, PPO), General ML Techniques | DL – Intermediate<br>RL – Intermediate<br>ML – Intermediate |
| **Current Focus** | Multi-agent RL in CARLA, Vision-based motion planning, Autonomous systems simulation | Research / Ongoing |


---

## Featured Projects

### 1) RL‑Based Pedestrian Controller in CARLA
**Stack:** Python · PyTorch · CARLA · Social‑LSTM · TD3 · Vision Transformer
**Highlights:** 
- Designed a multi-agent pedestrian controller integrating Social-LSTM and TD3 reinforcement learning.  
- Implemented BEV-based perception with Vision Transformer encoders.  
- Trained agents to simulate realistic and aggressive pedestrian behavior for autonomous vehicle safety.

**Repo:** [Dense Deep Reinforcement Learning](https://github.com/andytsai104/Dense-Deep-Reinforcement-Learning)

### 2) Image‑to‑Path Planning for MyCobot Pro 600
**Stack:** Python · OpenCV · ROS 2 · RViz · Gazebo · Forward/Inverse Kinematics  
**Highlights:** 
- Designed a **ROS 2-based control pipeline** for a 6-DOF **MyCobot Pro 600** robotic arm to follow paths extracted from camera images.  
- Developed an **image-processing workflow** using **OpenCV** for maze solving — color detection, morphological preprocessing, **skeletonization**, and **A\*** path planning.  
- Built a **digital twin (URDF)** of the robot using **SolidWorks** for visualization and motion testing in **RViz** and **Gazebo**.  
- Implemented **inverse kinematics** via a modified Denavit–Hartenberg model, enforcing the constraint  
  \\( \theta_2 + \theta_3 + \theta_4 = -\pi/2 \\) for physical feasibility.  
- Executed and tuned **joint trajectories** on both simulated and real hardware through **TCP/IP** control for smooth motion performance.
- Built a ROS 2 + Gazebo simulation for the **Dobot Magician Lite** robotic arm. 

**Repo:** [Robotics I](https://github.com/andytsai104/Robotics-I-RAS545/tree/main/Labs)



---

## Skills
- **Robotics:** Kinematics, motion planning, control (LQR, MPC basics), ROS 2  
- **ML/RL:** PyTorch, supervised/DL (CNN/LSTM/Transformer basics), TD3/SAC/PPO, dataset tooling  
- **Perception:** OpenCV, classical CV & tracking, BEV encoders  
- **Simulation:** CARLA, Gazebo/Isaac Sim (learning)  
- **Embedded/Systems:** C/C++, Python, RP2040, Linux tooling, Git/GitHub, CI basics  
- **Math:** Linear algebra, optimization, probability/stats

<!--

## Publications & Reports
- RAS 545 / Multi‑Robot Systems reports (selected): <links>  
- Capstone/Research notes (Robust RL for pedestrians): <link>

-->

## Contact
- Email: ctsai67@asu.edu  
- LinkedIn: [Chih-Hao (Andy) Tsai](https://www.linkedin.com/in/chih-hao-tsai/) 
- For collaborations/internships (CPT/OPT eligible), feel free to reach out.

---

<!--
### Repo Structure (recommended)
```
resume-portfolio/
├─ README.md                # this file
├─ Andy_Tsai_Resume.pdf     # exported resume
├─ media/                   # images, gifs for projects
│  ├─ carla_ped_demo.gif
│  └─ maze_solver.png
└─ projects/                # optional: brief writeups
   ├─ carla-pedestrian.md
   └─ mycobot-image-path.md
```
-->

<!--
### Maintenance Tips
- Keep **Featured Projects** to **3–5** with crisp bullets + visuals.
- Put **recruiter‑friendly summaries** up top; deep technical links in each project.
- Mirror **portfolio PDFs** required by ASU in this repo (if permitted), or link to Drive.
- Add a short **CHANGELOG** section for notable updates.
-->


<!--
### Badges (optional)
You can add CI/test coverage or tech stack badges if you use actions:
```
![Build](https://img.shields.io/badge/build-passing-brightgreen)
![CARLA](https://img.shields.io/badge/sim-CARLA-informational)
![PyTorch](https://img.shields.io/badge/ML-PyTorch-blue)
```
-->
