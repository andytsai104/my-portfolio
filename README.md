# Andy Tsai — Robotics & Autonomous Systems (M.S., ASU)

> Autonomous Vehicle Systems • Robotics • Machine Learning (DL & RL) • Perception (Computer Vision)

[LinkedIn](https://www.linkedin.com/) · [Email](mailto:youremail@asu.edu) · [GitHub](https://github.com/) · [Resume (PDF)](./Andy_Tsai_Resume.pdf)

---

## About
I’m a graduate student in **Robotics & Autonomous Systems (AI/EE)** at **Arizona State University**. My interests sit at the intersection of **autonomous driving simulation (CARLA)**, **robotics control**, and **learning-based perception and planning**. Previously, I earned a B.S. in Mechanical Engineering from National Taipei University of Technology and completed study-abroad coursework in Electrical Engineering at Aachen University of Applied Sciences.

I care about building **reliable, reproducible systems**—from low-level embedded control to high-level ML/RL stacks—and documenting the design trade‑offs along the way.

---

## Technical Highlights (concise)
- **Autonomous simulation:** Built a **pedestrian controller** in **CARLA** using **pretrained Social‑LSTM** for trajectory prediction and **RL (TD3)** for aggressive behavior modeling with BEV observations.
- **Robot kinematics & control:** Implemented **forward/inverse kinematics** (modified DH) for **Cobot/MyCobot Pro 600**; ROS 2 node for image‑based path skeletonization and IK with constraint \(\theta_2 + \theta_3 + \theta_4 = -\pi/2\).
- **Planning on images:** Maze solver pipeline: color detection → preprocessing → skeletonization → **A\*** on grid graph → robot execution.
- **Embedded/real‑time:** RP2040 / Pololu 3pi+ labs (GPIO masks, interrupts, debouncing, modal reactors); Linux/NVIDIA driver setup for OpenGL/GLX stability.
- **Robust/Deep RL:** Robust RL exploration for multi‑agent interactions; **vision encoder + actor‑critic** design for continuous control.

> Want the details? See **Featured Projects** below and linked repos.

---

## Featured Projects
> Replace links with your repositories and add a short GIF/screenshot per project in `/media/`.

### 1) RL‑Based Pedestrian Controller in CARLA
**Stack:** Python · PyTorch · CARLA · Social‑LSTM · TD3  
**Highlights:** BEV observation window, ring‑buffer trajectories, stochastic action head (softmax/gaussian), aggressive behavior tuning for AV planning edge cases.  
**Repo:** <link-to-repo> · **Demo:** <gif-or-mp4>

### 2) Image‑to‑Path Planning for MyCobot Pro 600
**Stack:** Python · OpenCV · ROS 2 · IK (modified DH)  
**Highlights:** Color segmentation → skeletonization → grid graph + **A\*** → motion execution; constraint **\(\theta_2 + \theta_3 + \theta_4 = -\pi/2\)**.  
**Repo:** <link-to-repo> · **Report:** <pdf-link>

### 3) Robotics I (RAS 545) Labs & Final
**Stack:** MATLAB/Python · Kinematics · Control  
**Highlights:** Clean lab READMEs, reproducible scripts, concise **Technical Highlights** per lab/homework.  
**Repo:** <link-to-repo>

---

## Selected Coursework @ ASU (grad)
- **Core:** EGR 501 Applied Linear Algebra; RAS 545 Robotics I  
- **EE/AI:** EEE 582 Linear System Theory; *EEE 591 Python for Rapid Engineering Solutions*; EEE 598 Deep Learning (Foundations & Applications); **EEE 598 Reinforcement Learning: Algorithms & Theory**; EEE 591 Computer Control Systems  
- **Robotics/Systems:** MAE 598 Multi‑Robot Systems; CSE 522 Real‑Time Embedded Systems

> Program: **MS‑RAS (AI/EE concentrations), 30 credits** with **Portfolio/Applied Project** culminating option.

---

## Skills
- **Robotics:** Kinematics, motion planning, control (LQR, MPC basics), ROS 2  
- **ML/RL:** PyTorch, supervised/DL (CNN/LSTM/Transformer basics), TD3/SAC/PPO, dataset tooling  
- **Perception:** OpenCV, classical CV & tracking, BEV encoders  
- **Simulation:** CARLA, Gazebo/Isaac Sim (learning)  
- **Embedded/Systems:** C/C++, Python, RP2040, Linux tooling, Git/GitHub, CI basics  
- **Math:** Linear algebra, optimization, probability/stats

---

## Publications & Reports
- RAS 545 / Multi‑Robot Systems reports (selected): <links>  
- Capstone/Research notes (Robust RL for pedestrians): <link>

---

## Contact
- Email: youremail@asu.edu  
- LinkedIn: <your‑linkedin>  
- For collaborations/internships (CPT/OPT eligible), feel free to reach out.

---

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

### Maintenance Tips
- Keep **Featured Projects** to **3–5** with crisp bullets + visuals.
- Put **recruiter‑friendly summaries** up top; deep technical links in each project.
- Mirror **portfolio PDFs** required by ASU in this repo (if permitted), or link to Drive.
- Add a short **CHANGELOG** section for notable updates.

---

### Badges (optional)
You can add CI/test coverage or tech stack badges if you use actions:
```
![Build](https://img.shields.io/badge/build-passing-brightgreen)
![CARLA](https://img.shields.io/badge/sim-CARLA-informational)
![PyTorch](https://img.shields.io/badge/ML-PyTorch-blue)
```

---

> **Next step**: Commit this README, add media previews, and link each project repo. Then create a profile README (special repo named `<your‑github‑username>`), and copy a shortened “About + Highlights + Links” section there.

