<h1 align="center">Sandeep Bhajantri</h1>
<h3 align="center">AI/ML Engineer · Computer Vision · Multi-Agent & GenAI Systems</h3>

<p align="center">
  AI & ML undergraduate at BMSIT, Bengaluru, building AI systems you can actually run:<br/>
  vision models, multi-agent APIs, and fraud-detection pipelines, with safety checks built in.<br/>
  <b>🥇 Winner, National Hackathon at IIIT Gwalior (500+ teams)</b> · Open to AI/ML internships
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sandeep-bhajantri">LinkedIn</a> ·
  <a href="mailto:sandeepbhajantri549@gmail.com">Email</a> ·
  <a href="https://github.com/sandep962/sandep962/raw/main/Resume.pdf">Resume (PDF)</a>
</p>

---

## 🏆 Recognition

| Year | Result | Project | Focus |
|------|--------|---------|-------|
| 2025 | 🥇 **Winner**, National Hackathon, IIIT Gwalior (500+ teams) | **TrapSense AI** | Wildlife camera-trap CV |
| 2025 | 🏅 **Top 4**, NMAM Hackfest | **Guardian AI** | Speech + NLP threat detection |
| 2025 | 🌍 Represented BMSIT, International BizThon (Yellow Network × IIT Delhi) | | |
| 2024 | 🚀 **National Finalist**, Hack2Future, IIIT Dharwad | [**Image Upscaling App**](https://github.com/Hack2Future-IIIT-Dharwad/byte_bundits) | GAN-based image restoration |

---

## 🔧 Featured Projects

### 🤖 [Multi-Agent Financial Research & Compliance Assistant](https://github.com/sandep962/Multi-Agent-Financial-Research-Compliance)
`Python` `FastAPI` `Agno` `Docker` `LLM agents`

Built for the **Valura AI Arena** assessment (practice → qualifying → final evaluation runs).
- 7 specialised agents (Router, Book QA, KYC, Notes, Market, Compliance, Verifier) answer client-specific questions through a FastAPI `/answer` endpoint.
- **Security by design:** strict per-client data isolation, retrieved notes treated as data not instructions (prompt-injection defence), and refusal of personalised investment advice.
- Structured responses with citations, confidence, abstain/refuse flags. Dockerised, with a scoring harness.

### 💳 [AI Financial Decision & Verification Layer](https://github.com/sandep962/AI-Financial-Decision-Verification-Layer)
`Python` `FastAPI` `React` `Vite` `Razorpay API`

Built for the **Razorpay AI Buildathon (Track 04: AI Finance Controller)**.
- Pipeline: `Event → Evidence → Decision → Policy Check → Execution → Verification → Audit Record`.
- Pulls real payment evidence from Razorpay Test Mode, enforces deterministic policy rules, then **re-checks the actual outcome** and reports "unverified" instead of claiming a recovery that didn't happen.
- Decision layer is decoupled, so an LLM can be plugged in without touching the safety controls.

### 🕸️ [Graph-Based Money Muling Detection](https://github.com/sandep962/MONEY_MULING)
`Python` `NetworkX` `Streamlit` `PyVis` `Pandas`

- Detects fraud rings in **unlabeled** transaction data with no trained model: fan-out, fan-in, circular flows and layering chains.
- Time-window sliding algorithms, DFS pathfinding, cycle detection and PageRank scoring.
- Streamlit dashboard with an interactive network graph and a JSON compliance report export.

### 🛰️ [Aerial GCP Pose Estimation & Shape Classification](https://github.com/sandep962/Aerial-GCP-Pose-Estimation-Shape-Classification-)
`PyTorch` `ResNet18` `Multi-task learning`

- Dual-head ResNet18 that predicts the **centre (x, y)** of Ground Control Point markers in drone imagery and classifies shape (Cross / Square / L-Shape).
- Trained on 996 images (300 test) at 512×512 with SmoothL1 + class-weighted cross-entropy and AdamW.
- Did EDA first and found and removed 4 unlabeled images. Handled mixed resolutions and class imbalance.

### 🔐 [Fingerprint Liveness Detection (Presentation Attack Detection)](https://github.com/sandep962/Fingerprint-Liveness-Detection)
`PyTorch` `MobileNetV3-Small` `Transfer learning`

Built for the **YellowSense Technologies** assignment.
- Classifies fingerprints as LIVE or SPOOF and evaluates with biometric metrics (**APCER, BPCER, EER**), with threshold calibration.
- **88.9% test accuracy (16/18)** on a small proof-of-concept set (SOCOFing, synthetic spoofs). Report with plots included.

### 🖼️ [Image Upscaling & Restoration App](https://github.com/Hack2Future-IIIT-Dharwad/byte_bundits)
`Flask` `BM3D` `ESRGAN` `GFPGAN`

Hack2Future (IIIT Dharwad) national finalist. Tiled image processing with a three-stage pipeline of BM3D denoising, ESRGAN super-resolution and GFPGAN face restoration, behind a web UI.

> **More work:** wildlife detection (**TrapSense AI**: YOLOv8 + FastAPI + AWS S3) and real-time audio threat detection (**Guardian AI**: Whisper + BERT). See [all repositories](https://github.com/sandep962?tab=repositories).

---

## 🧰 Skills

| | |
|---|---|
| **Languages** | `Python` `SQL` `JavaScript` |
| **ML / DL** | `PyTorch` `TensorFlow` `scikit-learn` · transfer learning, multi-task learning, GANs |
| **Computer Vision** | `OpenCV` `YOLOv8` `ResNet` `MobileNet` · keypoint regression, detection, restoration |
| **GenAI & Agents** | `LLM agents (Agno)` `LangChain` `OpenAI API` `Whisper` `BERT` · prompt-injection defence, grounded answers |
| **Backend & Tools** | `FastAPI` `Flask` `Streamlit` `React` `Docker` `Git` `AWS S3` `NetworkX` |

---

## 🎓 Education
**B.E. Artificial Intelligence & Machine Learning** · B.M.S. Institute of Technology and Management, Bengaluru · 7th Semester

---

## 📈 GitHub
<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=sandep962&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" />
</p>

---

## 🤝 Let's Connect
Open to **AI/ML internships**, applied research and collaborations in computer vision, multi-agent systems and trustworthy AI.

<p align="center">
  <a href="https://www.linkedin.com/in/sandeep-bhajantri"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:sandeepbhajantri549@gmail.com"><img src="https://img.shields.io/badge/Email-Get%20in%20Touch-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>
