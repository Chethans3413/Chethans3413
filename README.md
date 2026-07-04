<!-- ============================================================ -->
<!--              CHETHAN S · GITHUB SYSTEM PROFILE               -->
<!-- ============================================================ -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 250" width="100%" height="250">
  <defs>
    <filter id="glow-cyan" x="-30%" y="-30%" width="160%" height="160%">
      <feGaussianBlur stdDeviation="5" result="blur1" />
      <feGaussianBlur stdDeviation="10" result="blur2" />
      <feMerge>
        <feMergeNode in="blur2" />
        <feMergeNode in="blur1" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
  </defs>

  <style>
    @keyframes hover {
      0%, 100% { transform: translateY(0px); }
      50% { transform: translateY(-15px); }
    }
    @keyframes flap-left {
      0%, 100% { transform: rotate(0deg); }
      50% { transform: rotate(-22deg); }
    }
    @keyframes flap-right {
      0%, 100% { transform: rotate(0deg); }
      50% { transform: rotate(22deg); }
    }
    @keyframes pulse {
      0%, 100% { opacity: 0.8; }
      50% { opacity: 1; }
    }

    .dragon-system {
      animation: hover 4s ease-in-out infinite;
      transform-origin: 500px 125px;
    }
    .left-wing {
      animation: flap-left 2s ease-in-out infinite;
      transform-origin: 470px 115px;
    }
    .right-wing {
      animation: flap-right 2s ease-in-out infinite;
      transform-origin: 530px 115px;
    }
    .glowing-path {
      stroke: #00F0FF;
      stroke-width: 2.5;
      fill: none;
      stroke-linecap: round;
      stroke-linejoin: round;
      filter: url(#glow-cyan);
      animation: pulse 3s infinite;
    }
    .body-accent {
      stroke: #72FFFF;
      stroke-width: 1.5;
      fill: none;
      stroke-linecap: round;
      filter: url(#glow-cyan);
      opacity: 0.8;
    }
    .grid-lines {
      stroke: #0c2540;
      stroke-width: 1;
      opacity: 0.4;
    }
  </style>

  <g class="grid-lines">
    <line x1="0" y1="200" x2="1000" y2="200" />
    <line x1="0" y1="230" x2="1000" y2="230" />
    <path d="M 100 200 L 50 250 M 200 200 L 170 250 M 300 200 L 290 250 M 400 200 L 410 250 M 500 200 L 530 250 M 600 200 L 650 250 M 700 200 L 770 250 M 800 200 L 890 250 M 900 200 L 1000 250" />
  </g>

  <g class="dragon-system">
    <g class="left-wing">
      <path class="glowing-path" d="M 470 115 C 440 90, 390 60, 330 80 C 370 110, 420 125, 470 115 Z" />
      <path class="body-accent" d="M 330 80 C 380 90, 420 105, 470 115 M 360 85 C 400 95, 430 108, 470 115 M 390 90 C 420 100, 440 110, 470 115" />
    </g>

    <g class="right-wing">
      <path class="glowing-path" d="M 530 115 C 560 90, 610 60, 670 80 C 630 110, 580 125, 530 115 Z" />
      <path class="body-accent" d="M 670 80 C 620 90, 580 105, 530 115 M 640 85 C 600 95, 570 108, 530 115 M 610 90 C 580 100, 560 110, 530 115" />
    </g>

    <path class="glowing-path" d="M 450 120 C 470 100, 480 105, 500 105 C 520 105, 530 100, 550 120 C 565 135, 585 135, 600 125 C 615 115, 630 120, 645 130" />
    <path class="glowing-path" d="M 645 130 C 665 140, 690 135, 715 145 C 730 150, 745 145, 760 155 L 775 145 L 785 160 L 760 165 Z" />
    <path class="body-accent" d="M 760 155 L 785 160" />
    <path class="glowing-path" d="M 450 120 C 430 130, 415 125, 400 110 C 390 100, 385 85, 370 80 C 355 75, 340 85, 330 75 C 320 65, 310 65, 295 70 C 310 80, 325 80, 335 90 C 345 100, 360 105, 375 105 Z" />
    <path class="body-accent" d="M 370 80 L 375 70 M 365 82 L 368 75 M 340 85 L 342 78" />
    <circle cx="500" cy="115" r="5" fill="#72FFFF" filter="url(#glow-cyan)" />
  </g>
</svg>

<div align="center">
  <img src="./dragon.svg" width="900"/>
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=900&size=48&duration=3000&pause=800&color=00F0FF&center=true&vCenter=true&width=750&height=100&lines=Chethan+S" alt="Chethan S"/>
  <br/>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=900&color=72FFFF&center=true&vCenter=true&width=750&lines=%5B%E2%96%B6%5D+Initializing+Ocean+System...;%5B%E2%96%B6%5D+Loading+Neural+AI+Cores...;%5B%E2%96%B6%5D+Deploying+RAG+%26+LLM+Agents...;%5B%E2%96%B6%5D+Compiling+Android+Architectures...;%5B%E2%96%B6%5D+Connection+Established.+System+Online." alt="Typing SVG"/>
</div>

<br/>

<div align="center">
  <a href="https://linkedin.com/in/chethan-s-780-61b250">
    <img src="https://img.shields.io/badge/LinkedIn-0b1a30?style=for-the-badge&logo=linkedin&logoColor=00f0ff" height="30"/>
  </a>&nbsp;&nbsp;
  <a href="mailto:chethans3413@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-0b1a30?style=for-the-badge&logo=gmail&logoColor=00f0ff" height="30"/>
  </a>&nbsp;&nbsp;
  <a href="https://github.com/Chethans3413">
    <img src="https://img.shields.io/badge/GitHub-0b1a30?style=for-the-badge&logo=github&logoColor=00f0ff" height="30"/>
  </a>
</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 「 About Me 」

```javascript
const chethan = {
    alias    : "Chethans3413",
    role     : "AI & ML Engineer  ·  Android Developer",
    degree   : "B.E CSE (AI & ML) Graduate",
    location : "Bangalore, India 🇮🇳",
    focus    : ["Generative AI", "RAG Pipelines", "Agentic AI", "LLMs"],
    building : "AI-Powered Systems & Intelligent Android Applications",
    learning : ["LangChain", "MLOps", "Agentic Architectures"],
    patent   : "Co-Inventor — AI-Powered Disaster Prediction System 📜",
    funFact  : "I turned my 3rd-year project into a Published Patent 🌊"
};
```


- 🌊 Building **Generative AI Pipelines & Android Apps**
- 🤖 Exploring **LLMs, RAG & Agentic AI**
- 📱 Creating **Android Apps** with Kotlin & Jetpack Compose
- 📜 **Patent Co-Inventor** — AI Disaster Prediction System
- ⚡ Ask me about **Gen AI, ML, Android, or my Patent!**

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 「 Experience 」

**Android App Development Using Gen AI** &nbsp;|&nbsp; *Intern @ MindMatrix* &nbsp;|&nbsp; `Feb 2026 – May 2026`

- Built production Android apps using **Kotlin & Jetpack Compose**
- Integrated **Google AI Studio & Cloud Labs** for Gen AI workflows
- Managed **Firebase** integration, testing & debugging

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 「 Projects 」

<div align="center">
<table>

<tr>
<td width="50%" valign="top">

### 🤖 JARVIS AI Workstation
Production-grade AI orchestrator inspired by JARVIS — 40+ system endpoints, **Gemini 2.0** integration, real-time HUD & computer vision.

![JavaScript](https://img.shields.io/badge/JavaScript-0b1a30?style=flat-square&logo=javascript&logoColor=00f0ff)
![Gemini](https://img.shields.io/badge/Gemini_2.0-0b1a30?style=flat-square&logo=google&logoColor=00f0ff)

[![Repo](https://img.shields.io/badge/View_Repo-0b1a30?style=for-the-badge&logo=github&logoColor=00f0ff)](https://github.com/Chethans3413/Jarvis)

</td>
<td width="50%" valign="top">

### 🧠 Neural Document Reader
Next.js AI Document Agent — upload PDFs & query with local **RAG pipeline**. Built with LangChain.js, Ollama & Mistral 7B.

![Python](https://img.shields.io/badge/Python-0b1a30?style=flat-square&logo=python&logoColor=00f0ff)
![LangChain](https://img.shields.io/badge/LangChain-0b1a30?style=flat-square&logo=langchain&logoColor=00f0ff)

[![Repo](https://img.shields.io/badge/View_Repo-0b1a30?style=for-the-badge&logo=github&logoColor=00f0ff)](https://github.com/Chethans3413/Neural-Document-Reader)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🌍 AI Disaster Prediction `📜 Patent`
Full-stack AI disaster management platform — ML agents predict floods, hurricanes & earthquakes with intelligent routing & offline P2P emergency response.

![Python](https://img.shields.io/badge/Python-0b1a30?style=flat-square&logo=python&logoColor=00f0ff)
![TensorFlow](https://img.shields.io/badge/TensorFlow-0b1a30?style=flat-square&logo=tensorflow&logoColor=00f0ff)

[![Repo](https://img.shields.io/badge/View_Repo-0b1a30?style=for-the-badge&logo=github&logoColor=00f0ff)](https://github.com/Chethans3413/AI_Powered_Disaster_Prediction-main)

</td>
<td width="50%" valign="top">

### 🌾 Raitha Varta — Smart Farming
AI-powered agricultural companion for Karnataka farmers — **Gemini-driven** crop disease detection, live market prices & regional news.

![Kotlin](https://img.shields.io/badge/Kotlin-0b1a30?style=flat-square&logo=kotlin&logoColor=00f0ff)
![Firebase](https://img.shields.io/badge/Firebase-0b1a30?style=flat-square&logo=firebase&logoColor=00f0ff)

[![Repo](https://img.shields.io/badge/View_Repo-0b1a30?style=for-the-badge&logo=github&logoColor=00f0ff)](https://github.com/Chethans3413/Raitha-Varta-Agriculture-)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🥗 NutriPlan AI
Intelligent nutrition planner — generates personalized diet plans using AI based on health goals & dietary preferences.

![TypeScript](https://img.shields.io/badge/TypeScript-0b1a30?style=flat-square&logo=typescript&logoColor=00f0ff)
![AI](https://img.shields.io/badge/Generative_AI-0b1a30?style=flat-square&logo=google&logoColor=00f0ff)

[![Repo](https://img.shields.io/badge/View_Repo-0b1a30?style=for-the-badge&logo=github&logoColor=00f0ff)](https://github.com/Chethans3413/NutriPlan-AI)

</td>
<td width="50%" valign="top">

### 📊 Finance Dashboard
Full-stack finance dashboard — **React/Vite + Supabase**, interactive charts, role-based access control & CQRS architecture.

![TypeScript](https://img.shields.io/badge/TypeScript-0b1a30?style=flat-square&logo=typescript&logoColor=00f0ff)
![React](https://img.shields.io/badge/React-0b1a30?style=flat-square&logo=react&logoColor=00f0ff)

[![Repo](https://img.shields.io/badge/View_Repo-0b1a30?style=for-the-badge&logo=github&logoColor=00f0ff)](https://github.com/Chethans3413/Finance-Dashboard-Backend)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🐍 SNAKE_PROTOCOL
Retro-futurist cyber-grid simulation with integrated **synthwave audio system** — built with React & Tailwind CSS.

![TypeScript](https://img.shields.io/badge/TypeScript-0b1a30?style=flat-square&logo=typescript&logoColor=00f0ff)
![React](https://img.shields.io/badge/React-0b1a30?style=flat-square&logo=react&logoColor=00f0ff)

[![Repo](https://img.shields.io/badge/View_Repo-0b1a30?style=for-the-badge&logo=github&logoColor=00f0ff)](https://github.com/Chethans3413/-AI---Generated-Snake-Game-with-React-)

</td>
<td width="50%" valign="top">

### 📈 Customer Behavior Analysis
Data analytics project — customer behavior analysis using **Python, SQL & Power BI** for actionable business insights.

![Python](https://img.shields.io/badge/Python-0b1a30?style=flat-square&logo=python&logoColor=00f0ff)
![PowerBI](https://img.shields.io/badge/Power_BI-0b1a30?style=flat-square&logo=powerbi&logoColor=00f0ff)

[![Repo](https://img.shields.io/badge/View_Repo-0b1a30?style=for-the-badge&logo=github&logoColor=00f0ff)](https://github.com/Chethans3413/customer_behavior_analysis)

</td>
</tr>

</table>
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 「 Tech Arsenal 」

<div align="center">

**🧠 AI & Machine Learning**
<br/>
<img src="https://skillicons.dev/icons?i=python,tensorflow,pytorch,scikitlearn&theme=dark"/>
<br/>
`LLMs` &nbsp;·&nbsp; `RAG` &nbsp;·&nbsp; `LangChain` &nbsp;·&nbsp; `Prompt Engineering` &nbsp;·&nbsp; `OpenAI API` &nbsp;·&nbsp; `Hugging Face` &nbsp;·&nbsp; `FAISS`

<br/>

**📱 Mobile & Full Stack**
<br/>
<img src="https://skillicons.dev/icons?i=kotlin,java,androidstudio,firebase,react,nodejs,spring&theme=dark"/>

<br/>

**⚙️ Tools & DevOps**
<br/>
<img src="https://skillicons.dev/icons?i=docker,linux,git,github,vscode,mysql&theme=dark"/>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 「 GitHub Stats 」

<div align="center">

<img height="182" src="https://streak-stats.demolab.com/?user=Chethans3413&hide_border=true&background=0b1a30&stroke=00f0ff&ring=0096c7&fire=00f0ff&currStreakLabel=00f0ff&sideLabels=72ffff&dates=72ffff&currStreakNum=00f0ff"/>
&nbsp;&nbsp;
<img height="182" src="https://github-readme-stats-salesp07.vercel.app/api/top-langs/?username=Chethans3413&layout=compact&hide_border=true&bg_color=0b1a30&title_color=00f0ff&text_color=72ffff&langs_count=8"/>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 「 Hall of Fame 」

<div align="center">

| 🏅 Achievement | 📜 Certification |
|:---|:---|
| 📜 **Patent Co-Inventor** — AI-Powered Disaster Prediction System | ☁️ **Oracle Cloud** — Gen AI Certified Professional |
| 🥈 **2nd Place** — Mini Project Competition | 🤖 **IBM** — AI Fundamentals |
| 🎓 **CSI Member** — Computer Society of India, SVIT | 🎓 **NPTEL (IIT Kanpur)** — Deep Learning |
| | ☁️ **AWS** — Amazon EC2 |

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 「 Contribution Snake 」

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Chethans3413/Chethans3413/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Chethans3413/Chethans3413/output/github-snake.svg"/>
    <img alt="github-snake" src="https://raw.githubusercontent.com/Chethans3413/Chethans3413/output/github-snake-dark.svg"/>
  </picture>
</div>

<br/>

<div align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">
</div>

<div align="center">
  <sub>✨ Crafted with ❤️ by <a href="https://github.com/Chethans3413"><b>Chethan S</b></a> &nbsp;·&nbsp; Building the future, one commit at a time &nbsp;·&nbsp; © 2026</sub>
</div>
