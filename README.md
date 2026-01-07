<br>
<h1 align="center">Visual SLAM with Augmented Reality</h1>
<br>

![Python](https://img.shields.io/badge/Python-3.11-blue?style=flat-square&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter&logoColor=white)
![Open3D](https://img.shields.io/badge/Open3D-0.17-purple?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-4.7-blue?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1.26-blue?style=flat-square&logo=numpy&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=flat-square&logo=github&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Size](https://img.shields.io/github/repo-size/hamaylzahid/visual-slam-augmented-reality?style=flat-square)

This repository demonstrates an **offline monocular Visual SLAM pipeline** implemented using **Python** and **OpenCV**, with **3D augmented reality overlay**. The project combines **computer vision**, **visual odometry**, and **augmented reality (AR)** to simulate ARCore/ARKit functionality using classical CV techniques.

---

<br>
<h2 align="center">Table of Contents</h2>
<br>

1. [Project Overview](#project-overview)  
2. [Visual Explanation](#visual-explanation)  
3. [Demo Output](#demo-output)  
4. [Tech Stack](#tech-stack)  
5. [How to Run](#how-to-run)  
6. [Key Learning Outcomes](#key-learning-outcomes)  
7. [Future Improvements](#future-improvements)
8. [Contact & Contribution](#contact--contribution)  
9. [License](#license)  


---

<br>
<h2 align="center">Project Overview</h2>
<br>

The Visual SLAM pipeline performs:

- Detection and tracking of visual features in consecutive video frames  
- Camera motion estimation using **essential matrix** and **epipolar geometry**  
- Projection of 3D axes into the real-world scene as an **augmented reality overlay**  
- Visualization of feature correspondences and camera trajectory  

This project demonstrates practical **offline SLAM**, similar to **ARCore / ARKit**, without relying on external libraries beyond OpenCV.

---

<br>
<h2 align="center">Visual Explanation</h2>
<br>

- **Feature points (blue/red dots):** Detected corners and edges in frames  
- **Green lines:** Tracked correspondences between frames  
- **3D AR axes:** Virtual objects projected into the real world  

Green lines may appear/disappear due to features moving out of view or changes in tracking confidence—this is expected in **Visual SLAM** pipelines.

---

<br>
<h2 align="center">Demo Output</h2>
<br>

![Demo Output](assets/ar_output.gif)  

This GIF showcases **feature tracking, camera pose estimation, and 3D AR axes projection**.

---

<br>
<h2 align="center">Tech Stack</h2>
<br>

- **Python 3.x**: Main programming language  
- **OpenCV 4.x**: Feature detection, tracking, pose estimation  
- **NumPy**: Numerical computation and matrix operations  
- **Jupyter Notebook**: Interactive demonstration and visualization
- -**Open3D**

---

<br>
<h2 align="center">How to Run</h2>
<br>

1. Clone the repository:

```bash
git clone https://github.com/hamaylzahid/visual-slam-augmented-reality.git
cd visual-slam-augmented-reality
```

2.Install dependencies:

```pip install -r requirements.txt```


3.Open the Jupyter Notebook:

```jupyter notebook Visual_SLAM_Augmented_Reality.ipynb```


The processed output will show tracked features, camera motion, and 3D AR axes.


The processed output will show **tracked features, camera motion, and 3D AR axes**.

<br>
<h2 align="center">Key Learning Outcomes</h2>
<br>

- Understanding **monocular Visual SLAM fundamentals**  
- Feature detection and tracking using **ORB**  
- Camera pose estimation with **essential matrix** and **epipolar geometry**  
- 3D augmented reality projection  
- Designing practical **computer vision pipelines**  

<br>
<h2 align="center">Future Improvements</h2>
<br>

- Integrate **bundle adjustment** for more accurate pose estimation  
- Add **3D point triangulation** to generate sparse maps  
- Implement **loop closure detection** for consistent mapping  
- Real-time optimization for faster processing  
- IMU fusion for improved pose accuracy  

---

<br>
<h2 align="center">Contact & Contribution</h2>
<br>

<p align="center">
  Have feedback, want to collaborate, or want to extend this project?<br>
  <strong>Let’s connect and enhance Visual SLAM and Augmented Reality systems together.</strong>
</p>


<p align="center">
  <a href="https://github.com/hamaylzahid/visual-slam-augmented-reality/stargazers">
    <img src="https://img.shields.io/badge/Star%20This%20Project-Give%20a%20Star-yellow?style=for-the-badge&logo=github" alt="Star Badge">
  </a>
  <a href="https://github.com/hamaylzahid/visual-slam-augmented-reality/pulls">
    <img src="https://img.shields.io/badge/Contribute-Pull%20Requests%20Welcome-2ea44f?style=for-the-badge&logo=github" alt="PR Badge">
  </a>
</p>

<p align="center">
  Found this project helpful? Give it a star.<br>
  Want to improve it? Submit a pull request and join the development.<br>
</p>

<br>
<h2 align="center">License</h2>
<br>

<p align="center">
  This project is licensed under the <strong>MIT License</strong> and is open for use, modification, and distribution.
</p>

<p align="center">
  <strong>Developed with Visual SLAM, 3D AR, and computer vision principles in mind.</strong>
</p>

<p align="center">
  <a href="https://github.com/hamaylzahid">
    <img src="https://img.shields.io/badge/GitHub-%40hamaylzahid-181717?style=flat-square&logo=github" alt="GitHub">
  </a>
  &nbsp;•&nbsp;
  <a href="mailto:maylzahid588@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-red?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
  &nbsp;•&nbsp;
  <a href="https://github.com/hamaylzahid/visual-slam-augmented-reality">
    <img src="https://img.shields.io/badge/Repo-Link-blueviolet?style=flat-square&logo=github" alt="Repo">
  </a>
  <br>
  <a href="https://github.com/hamaylzahid/visual-slam-augmented-reality/fork">
    <img src="https://img.shields.io/badge/Fork%20This%20Project-Contribute%20to%20SLAM-2ea44f?style=flat-square&logo=github" alt="Fork">
  </a>
</p>

<p align="center">
  <sub><i>Designed for Visual SLAM, 3D AR projection, and real-time mapping showcase.</i></sub>
</p>

