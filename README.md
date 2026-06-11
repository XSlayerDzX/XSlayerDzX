<h1 align="center">Abdelmalek Hissous</h1>

<p align="center">
  <b>CS Student @ ESI-SBA</b> &nbsp;·&nbsp; Machine Learning &nbsp;·&nbsp; Reinforcement Learning &nbsp;·&nbsp; Computer Vision
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/abdelmalek-hissous-835991340/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://github.com/XSlayerDzX">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

I build ML systems end-to-end — from raw data collection to trained models running in production. Most of what I work on sits at the intersection of reinforcement learning, computer vision, and practical engineering: the kind of stuff that has to actually run, not just score well on a benchmark.

Currently finishing my CS degree at ESI-SBA while pushing the boundaries of what a solo (well, duo) project can pull off.

---

## 🏆 ArenaBrain — Autonomous Clash Royale Agent

> *Built with [Mousli Tayeb](https://github.com/mousli-tayeb) · Supervised by Prof. Belkacem Khaldi*

The flagship project. An autonomous agent that plays Clash Royale in real time, paired with a full analytics dashboard to monitor training runs.

**The pipeline:**

| Stage | What happens |
|---|---|
| 🎮 **Screen capture** | Real-time frame extraction from BlueStacks |
| 👁️ **Perception** | Unit, tower & card detection via **RF-DETR** |
| 🧠 **Decision making** | LSTM policy — warm-started with **Behavior Cloning**, fine-tuned with **PPO** |
| 📊 **Monitoring** | Live training stats pushed to the **ArenaBrain** web dashboard via API |
| 🏅 **Reward shaping** | Tower HP OCR (post-game), elixir overflow penalties, terminal win/loss signal |

The agent learns from human replays first, then improves through self-play. The PPO stage is showing solid signal — it just needs compute time to fully converge. That chapter is still open.

**Repo:** [Reinforcement-Learning-AiAgent](https://github.com/XSlayerDzX/Reinforcement-Learning-AiAgent)

---

## 🛠️ Other Projects

| Project | What it does |
|---|---|
| [**House Price ML Pipeline**](https://github.com/XSlayerDzX/house-price-ml-pipeline) | End-to-end pipeline from feature engineering to deployed prediction API |
| [**ML Microservice — Anomaly Detection**](https://github.com/XSlayerDzX/Ml_Microservice_Anomaly_Detection) | Containerised microservice for real-time anomaly detection |

---

## ⚙️ Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
</p>

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=XSlayerDzX&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="160"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=XSlayerDzX&layout=compact&theme=tokyonight&hide_border=true" height="160"/>
</p>

---

## 🔭 What I'm Focused On

- Pushing the ArenaBrain PPO training further — more games, better reward signal
- Deepening my understanding of modern CV architectures
- Building things that ship, not just things that train

---

<p align="center">
  <i>Open to internships, collaborations, and any project that's actually interesting.</i>
</p>
