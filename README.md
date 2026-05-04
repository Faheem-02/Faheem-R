# Hey, I'm Faheem 👋

I'm an AI Systems Engineer based in Hyderabad, India.

I don't just wire up LLM calls - I build the layer around them. The part that plans, routes, handles failure, falls back gracefully, and gives you traceable output instead of a black box. After spending time at ISRO automating satellite image pipelines, I started applying the same thinking to AI systems: define the states, control the execution, design for what breaks.

Currently looking for roles where I can build AI pipelines, agent systems, or LLM-integrated backends that actually work in production.

---

## 🔧 What I Build

**AI Systems & Agents**

Systems that don't just chat - they plan tasks, route intent, execute actions, and recover from failure. Built without LangChain because understanding the internals matters.

**RAG Pipelines**

Retrieval-augmented generation with source tracking, confidence scoring, and hallucination guards. Not a wrapper, a pipeline with defined stages and observable behaviour.

**ML & Computer Vision**

Geospatial image segmentation from my ISRO internship - U-Net baseline (IoU 0.4013 on 135 ISRO satellite images, 7 classes) extended to U-Net + ResNet34 (Mean IoU 0.7984 on 21,000-image landcover.ai dataset). Also explored image super-resolution with SRCNN and SRGAN on satellite imagery.

---

## 🚀 Projects

| Project | What it does | Stack |
|---|---|---|
| [**Aletheia RAG Engine**](https://github.com/Faheem-02/Alethia-RAG-Engine) | Retrieval → reranking → generation with source verification and mock fallback | Python, FAISS, FastAPI |
| [**Nexus AI Agent**](https://github.com/Faheem-02/Nexus-AI-Agent) | Goal → plan → execution with Playwright browser automation and controlled loops | Python, Playwright, FastAPI |
| [**Modular Voice AI**](https://github.com/Faheem-02/Nexus-Voice-AI-System) | Speech → intent → handler → TTS with provider abstraction | Python, FastAPI, STT/TTS APIs |
| [**LULC Segmentation — U-Net (ISRO)**](https://github.com/Faheem-02/Level-I-LULC-Classification-using-U-Net-ISRO-Internship-) | 7-class satellite image segmentation on 135 ISRO images — IoU 0.4013, ~90% accuracy | Python, TensorFlow, U-Net, QGIS |
| [**LULC Segmentation — ResNet34 Extension**](https://github.com/Faheem-02/LULC-Classification-U-Net-ResNet34) | U-Net + ResNet34 on 21,000-image dataset — Mean IoU 0.7984, precision 0.9109 | Python, TensorFlow, ResNet34 |
| [**Comparative Study: Image Super-Resolution**](https://github.com/Faheem-02/Comparative-Study-of-Deep-Learning-Models-for-Image-Super-Resolution) | SRCNN vs SRGAN comparison on satellite imagery — LR to HR reconstruction pipeline | Python, TensorFlow, SRCNN, SRGAN |

---

## 🧠 How I Think About Systems

A few principles I arrived at independently (and later found in distributed systems literature):

- **State before logic** - define your execution states explicitly; hidden transitions cause the worst bugs
- **Design for failure first** - if you can't describe how a component fails, you don't understand it yet
- **Backpressure over retries** - hard limits beat optimistic retry loops every time
- **Observability is not optional** - if you can't trace what happened, you can't fix it

---

## 🛠️ Skills
![Python](https://img.shields.io/badge/Python-Primary-blue?logo=python) 
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white) 
![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white) 
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) 
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)
![Computer Vision](https://img.shields.io/badge/ComputerVision&NLP-Deep%20Learning-yellow)

```
AI/LLM       →  RAG pipelines, Agent workflows, LLM API integration, FAISS, Prompt engineering
ML           →  TensorFlow, U-Net, ResNet34, SRCNN, SRGAN, Image Segmentation, NLP, IoU evaluation
Backend      →  Python, FastAPI, REST APIs, Config-driven architecture
Automation   →  Playwright, QGIS, structured logging
Cloud        →  AWS (Cloud Foundations + ML Foundations, Credly certified)
Concepts     →  State machines, Control loops, DAG execution, Actor model, Mock mode systems
```

---

## 📫 Let's connect

- 📧 [Faheemar3@gmail.com](mailto:Faheemar3@gmail.com)
- 🔗 LinkedIn: https://www.linkedin.com/in/faheem2144/
- 📍 Hyderabad, India — open to remote and hybrid roles

---

*"I think in systems first and reach for code second."*
