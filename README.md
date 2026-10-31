<!-- Header banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Ebna%20Sina&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Data%20Science%20%C2%B7%20Research%20Data%20Management%20%C2%B7%20Berlin&descSize=16&descAlignY=58&descColor=cfe8ef" width="100%" alt="header"/>
</p>

<!-- Typing line -->
<p align="center">
  <a href="https://github.com/sina-778">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3500&pause=900&color=2C9FB8&center=true&vCenter=true&width=620&lines=MSc+Data+Science+%40+BHT+Berlin;Working+Student+%40+Paul-Drude-Institut;Built+FootScout+%E2%9A%BD+AI+player+scouting;Routing+LLMs+with+System+1+models+%F0%9F%A7%A0;Running+a+NOMAD+Oasis+for+research+data" alt="Typing SVG"/>
  </a>
</p>

<!-- Contact buttons -->
<p align="center">
  <a href="https://www.linkedin.com/in/ebna-sina/"><img src="https://img.shields.io/badge/LinkedIn-ebna--sina-203a43?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0f2027" alt="LinkedIn"/></a>
  <a href="https://github.com/pdi-sina"><img src="https://img.shields.io/badge/Work%20GitHub-pdi--sina-203a43?style=for-the-badge&logo=github&logoColor=white&labelColor=0f2027" alt="Work GitHub"/></a>
  <img src="https://img.shields.io/badge/Based%20in-Berlin-203a43?style=for-the-badge&logo=googlemaps&logoColor=white&labelColor=0f2027" alt="Berlin"/>
</p>

---

## 👋 About Me

I'm **Sina**, a data science student who enjoys turning messy data into things people can actually use, from research data platforms to AI tools you can play with in the browser. I grew up in Dhaka, Bangladesh 🇧🇩 and now live and study in Berlin 🇩🇪.

```yaml
name:       Ebna Sina
location:   Berlin, Germany
studying:   MSc Data Science @ Berliner Hochschule für Technik (BHT)
working:    Working Student, Research Data Management @ Paul-Drude-Institut (PDI)
focus:      [recommender systems, LLM routing, research data infrastructure]
learning:   [LLM fine-tuning (LoRA), German 🇩🇪]
off_screen: football ⚽
```

---

## 🚀 Projects

<table>
<tr>
<td width="50%" valign="top">

### ⚽ [FootScout](https://github.com/sina-778/footscout)
**AI football scouting engine.** *"Find me a striker like Haaland under €80M"*, and it does.

- 🔍 Natural-language search across **1,474 players**, 5 leagues + WC 2026
- 🧬 **416-dim hybrid embeddings** (per-90 stats + Sentence-BERT) with cosine similarity
- 💎 Budget Scout & Hidden Gems modes, radar charts
- 🎛️ Tuned with Optuna, tracked with W&B

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![SBERT](https://img.shields.io/badge/Sentence--BERT-2C9FB8?style=flat-square&labelColor=0f2027)

<a href="https://footscout.streamlit.app/"><img src="https://img.shields.io/badge/▶%20Live%20demo-2C9FB8?style=for-the-badge&labelColor=0f2027" alt="Live demo"/></a>

</td>
<td width="50%" valign="top">

### 🧠 [Hybrid Brain: System 1 routes, System 2 answers](https://github.com/sina-778/system1-demo)
**Live classroom demo of System 1 decision models** routing tasks to LLMs on the GWDG supercomputer.

- ⚡ A System 1 model scores each task with **probabilities** (which specialist? needs reasoning? how hard?) instead of generating text
- 🚦 A **gatekeeper** escalates low-confidence tasks to a 675B model
- 🏎️ Head-to-head with an LLM-as-router: typically **20–30× faster**, and never returns broken JSON
- 💻 Runs via API (Jev) or **fully local** with CLM-8B on llama.cpp

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-2C9FB8?style=flat-square&labelColor=0f2027)

<a href="https://github.com/sina-778/system1-demo"><img src="https://img.shields.io/badge/View%20code-203a43?style=for-the-badge&logo=github&logoColor=white&labelColor=0f2027" alt="Code"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🗄️ NOMAD Oasis @ PDI Berlin *(work)*

I maintain the institute's self-hosted **[NOMAD Oasis](https://nomad-lab.eu/)**, where materials scientists store, search and share their research data.

- 🧩 Extend the institute's **NOMAD plugin** (Python): data schemas, normalizers and search apps for MBE growth, substrates and samples
- 🔬 Contributed upstream to **FAIRmat** (`readers-xrd`, `nomad-measurements`): automatic instrument linking and timestamps for XRD data
- 🔐 Set up **HTTPS** with Nginx, so login works in NOMAD's new web interface
- 🐳 Run Docker test environments for colleagues, with monitoring via Grafana & Prometheus
- ✅ Keep plugin code passing CI (Ruff, pytest on GitHub Actions)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</td>
<td width="50%" valign="top">

### 📉 LoRA Paper Project *(in progress)*
Advanced ML group project at BHT on **LoRA** (Hu et al., ICLR 2022): fine-tuning large models by training small low-rank matrices instead of all the weights.

- 📚 Studying the method and its trade-offs
- 🔬 Reproducing key results on a smaller model

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

</td>
</tr>
</table>

<p align="center">
  <b>Earlier work:</b>
  <a href="https://github.com/sina-778/pattern_lab">🔬 pattern_lab</a> (pattern recognition, Python) ·
  <a href="https://github.com/sina-778/Student_Management_System">🎓 Student Management System</a> (Java) ·
  <a href="https://github.com/sina-778/Free-Time-Tutoring">📚 Free-Time-Tutoring</a> (HTML/CSS)
</p>

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,js,html,css,mysql,postgres&theme=dark" alt="Languages"/>
  <br/><br/>
  <img src="https://skillicons.dev/icons?i=pytorch,sklearn,docker,nginx,linux,git,github,vscode&theme=dark" alt="Tools"/>
</p>

---

## 📊 GitHub Activity

I use two accounts: **this one for personal & study projects**, and **[@pdi-sina](https://github.com/pdi-sina) for my work at the Paul-Drude-Institut** (mostly private institute repos, so only contribution counts are visible).

<table align="center">
<tr>
<td align="center"><b>🧑‍💻 Personal · <a href="https://github.com/sina-778">@sina-778</a></b></td>
<td align="center"><b>🔬 Work @ PDI · <a href="https://github.com/pdi-sina">@pdi-sina</a></b></td>
</tr>
<tr>
<td align="center"><img src="https://streak-stats.demolab.com?user=sina-778&theme=transparent&hide_border=true&ring=2C9FB8&fire=2C9FB8&currStreakLabel=2C9FB8&sideLabels=2C9FB8&dates=8b949e&currStreakNum=8b949e&sideNums=8b949e&stroke=30363d" alt="Personal streak"/></td>
<td align="center"><img src="https://streak-stats.demolab.com?user=pdi-sina&theme=transparent&hide_border=true&ring=2C9FB8&fire=2C9FB8&currStreakLabel=2C9FB8&sideLabels=2C9FB8&dates=8b949e&currStreakNum=8b949e&sideNums=8b949e&stroke=30363d" alt="Work streak"/></td>
</tr>
</table>

---

## 🎓 Education

| Degree | Institution | |
|---|---|---|
| 🎓 **MSc Data Science** | Berliner Hochschule für Technik (BHT), Berlin | *ongoing* |
| 🎓 **Bachelor's** | United International University (UIU), Dhaka | |

---

## 🤝 Let's Connect

I'm always happy to chat about **recommender systems, LLMs, research data management or football analytics** ⚽.
The easiest way to reach me is on **[LinkedIn](https://www.linkedin.com/in/ebna-sina/)**.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" width="100%" alt="footer"/>
</p>
