<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=30&duration=2800&pause=700&color=00C896&center=true&vCenter=true&width=900&lines=SHAUNAK+MAJUMDAR;AI%2FML+%E2%80%A2+COMPUTER+VISION+%E2%80%A2+MULTIMODAL+AI;RESEARCH+%E2%80%A2+BUILD+%E2%80%A2+MEASURE;TURNING+IDEAS+INTO+INTELLIGENT+SYSTEMS" />

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&height=180&section=header&text=AI%20%2F%20ML%20%2F%20RESEARCH&fontSize=35&fontColor=ffffff&animation=fadeIn&fontAlignY=35&color=0:111827,50:0f766e,100:020617" width="100%"/>

<br>

<a href="https://github.com/23ME30056">
<img src="https://img.shields.io/badge/GitHub-23ME30056-181717?style=for-the-badge&logo=github"/>
</a>

<a href="#">
<img src="https://img.shields.io/badge/IIT%20Kharagpur-Researcher-0f766e?style=for-the-badge"/>
</a>

<a href="#">
<img src="https://img.shields.io/badge/Computer%20Vision-Research-2563eb?style=for-the-badge"/>
</a>

</div>

---

# 👋 Hey, I'm Shaunak.

> **I build AI systems and study the representations behind them.**

I'm an undergraduate researcher at **IIT Kharagpur**, working across **Computer Vision, Self-Supervised Learning, Multimodal AI, LLM systems and representation learning**.

My current obsession:

```text
                    HOW DO MACHINES REPRESENT THE WORLD?
                                  │
             ┌────────────────────┼────────────────────┐
             ▼                    ▼                    ▼
       OBJECTS & PARTS       VISION + LANGUAGE       AI SYSTEMS
             │                    │                    │
           JEPA                  VLMs                 RAG
           SAEs                Qwen-VL              Agents
            SSL                 SAM3                Retrieval
           DINOv2               VQA                  APIs
```

---

# 🧬 Research Universe

```mermaid
mindmap
  root((Shaunak))
    Computer Vision
      DINOv2
      ViT
      YOLO
      SAM3
      Grad-CAM
    Representation Learning
      JEPA
      Self-Supervised Learning
      Sparse Autoencoders
      Object-centric Learning
    Multimodal AI
      Qwen-VL
      VLMs
      VQA
      Grounding
      Dense Counting
    LLM Systems
      RAG
      Multi-Agent Systems
      Qdrant
      BM25
      LangGraph
    Engineering
      PyTorch
      FastAPI
      Docker
      Streamlit
```

---

# 🔬 What I'm Working On

<div align="center">

<table>
<tr>
<td width="50%" align="center">

## 🧩 PART-CENTRIC JEPA

**Object → Part → Scene**

Exploring encoder-agnostic world models with **sparse autoencoders and disentangled latent representations**.

`JEPA` `SAE` `ViT` `Representation Learning`

</td>

<td width="50%" align="center">

## 🛰️ DRISHTI

**See → Ground → Reason**

A unified VLM framework for satellite imagery.

`Qwen-VL` `QLoRA` `DPO` `SAM3`

</td>
</tr>

<tr>
<td width="50%" align="center">

## 🛡️ PROJECT RAKSHAK

**Sense → Retrieve → Reason → Respond**

A 15-agent multimodal disaster-response system.

`Gemini` `DINOv2` `Qdrant` `BM25` `Whisper` `CLAP`

</td>

<td width="50%" align="center">

## 🔍 CRACK DETECTION

**Learn with less supervision**

CrANet + CBAM + SSL + DINOv2 for label-efficient crack detection.

`PyTorch` `SSL` `DINOv2` `Grad-CAM`

</td>
</tr>
</table>

</div>

---

# 📸 Research Gallery

<div align="center">

<!-- Replace these with actual project screenshots stored in /assets -->

<img src="./assets/jepa-overview.png" width="48%" />
<img src="./assets/rakshak-architecture.png" width="48%" />

<br><br>

<img src="./assets/drishti-vlm.png" width="48%" />
<img src="./assets/cranet-gradcam.png" width="48%" />

</div>

<br>

<sub>
↑ Visual research artifacts: model architectures, qualitative results, attention maps, Grad-CAM visualizations and system diagrams.
</sub>

---

# 🧠 How My Systems Think

### Multimodal Disaster Response

```mermaid
flowchart LR
    A["📷 Image"] --> B["🧠 Vision Encoder"]
    C["🎙️ Audio"] --> D["🔊 Whisper / CLAP"]
    E["📄 Documents"] --> F["📚 Retrieval"]

    B --> G["🤖 Agent Orchestrator"]
    D --> G
    F --> G

    G --> H["🔎 Dense + Sparse Retrieval"]
    H --> I["🧩 RRF Rescoring"]
    I --> J["💬 Gemini Reasoning"]
    J --> K["🚨 Emergency Response"]
```

---

# 🛰️ Multimodal Vision

```mermaid
flowchart LR
    A["Satellite Image"] --> B["Qwen-VL"]
    A --> C["SAM3"]
    
    B --> D["Captioning"]
    B --> E["VQA"]
    B --> F["Grounding"]

    C --> G["Pyramidal Tiling"]
    G --> H["Dense Object Counting"]

    D --> I["🌍 Scene Understanding"]
    E --> I
    F --> I
    H --> I
```

---

# 🧩 Representation Learning

```mermaid
flowchart TB
    A["Image"] --> B["Vision Encoder"]
    B --> C["Object Representation"]
    C --> D["Part Discovery"]

    D --> E["Sparse Autoencoder"]

    E --> F["Latent 1"]
    E --> G["Latent 2"]
    E --> H["Latent 3"]

    F --> I["Object"]
    G --> J["Parts"]
    H --> K["Scene Structure"]

    I --> L["Part-Centric World Model"]
    J --> L
    K --> L
```

---

# 📈 Numbers I Care About

<div align="center">

<table>
<tr>

<td align="center">
<h2>40.2%</h2>
<b>Detection Gain</b>
<br>
<sub>with only 5% labelled data</sub>
</td>

<td align="center">
<h2>99.7%</h2>
<b>Classification</b>
<br>
<sub>DINOv2 · 30ms inference</sub>
</td>

<td align="center">
<h2>37%</h2>
<b>Counting Improvement</b>
<br>
<sub>Adaptive Grounding</sub>
</td>

<td align="center">
<h2>40×</h2>
<b>Retrieval Speedup</b>
<br>
<sub>Qdrant Binary Quantization</sub>
</td>

</tr>
</table>

</div>

---

# 📊 Research Impact

```mermaid
xychart-beta
    title "Selected relative improvements"
    x-axis ["Detection", "Counting", "Retrieval"]
    y-axis "Improvement / speedup" 0 --> 45
    bar [40.2, 37, 40]
```

<sub>
Detection and counting are percentage improvements; retrieval is a reported speedup factor. The chart is intended as a visual snapshot rather than a directly comparable scientific benchmark.
</sub>

---

# 🏗️ My AI Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,opencv,cpp,c,java,git,docker,fastapi,postgres&perline=11"/>

<br><br>

<img src="https://skillicons.dev/icons?i=github,linux,aws,azure,streamlit&perline=8"/>

</div>

<br>

<div align="center">

`PyTorch` · `Hugging Face` · `Qwen-VL` · `Gemini` · `DINOv2` · `YOLO` · `SAM3`

`Qdrant` · `FAISS` · `ChromaDB` · `BM25` · `LangGraph` · `FastAPI` · `Docker`

</div>

---

# 🏆 Selected Achievements

<div align="center">

| 🏆 Achievement                     |         Result         |
| :--------------------------------- | :--------------------: |
| Goldman Sachs India Hackathon 2026 |  **National Finalist** |
| Inter IIT Tech Meet 14.0 × ISRO    |       **🥇 Gold**      |
| Hack The Future 2025               |   **🥉 National 3rd**  |
| Kharagpur Data Science Hackathon   |  **Top 10 / 10,000+**  |
| EMPOWER Student Design Challenge   | **🥇 National Winner** |

</div>

---

# 📊 GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=23ME30056&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&rank_icon=github"/>

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=23ME30056&layout=donut&hide_border=true&langs_count=8"/>

<br><br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=23ME30056&hide_border=true"/>

</div>

---

# 🗺️ The Road So Far

```mermaid
timeline
    title My AI Journey

    2024 : ML foundations
         : Classical ML
         : NLP
         : RAG systems

    2025 : Computer Vision
         : Self-Supervised Learning
         : DINOv2
         : Qwen-VL
         : Multimodal AI

    2026 : Representation Learning
         : Part-Centric JEPA
         : Multi-Agent AI
         : Efficient Retrieval
         : Research
```

---

# 🔭 Currently Exploring

<div align="center">

`OBJECT-CENTRIC LEARNING`

↓

`PART-LEVEL REPRESENTATIONS`

↓

`WORLD MODELS`

↓

`MULTIMODAL REASONING`

↓

`AGENTIC AI`

</div>

---

# 📚 Research Philosophy

<div align="center">

> **Don't just make the model work.**
>
> **Understand what it learned.**
>
> **Measure why it works.**
>
> **Then make it better.**

</div>

---

# 📫 Let's Connect

<div align="center">

<a href="https://github.com/23ME30056">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="YOUR_LINKEDIN_URL">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:YOUR_EMAIL">
<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>

<br>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:020617,50:0f766e,100:00c896"/>

### `Research deeply. Build relentlessly. Measure everything.`

</div>


<!---
23ME30056/23ME30056 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
