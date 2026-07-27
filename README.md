<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=220&section=header&text=Adam%20Eehan&fontSize=65&fontColor=e94560&fontAlignY=38&desc=AI%20Engineer%20%7C%20Open%20Source%20Enthusiast&descAlignY=51&descAlign=50" width="100%" />
</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&pause=1000&color=E94560&center=true&vCenter=true&width=650&lines=Building+AI+that+matters+%F0%9F%A4%96;Python+%7C+C+%7C+C%2B%2B+%7C+JavaScript;AI+Engineer+%26+Software+Developer;Always+learning%2C+always+building+%F0%9F%9A%80)](https://git.io/typing-svg)

![Profile Views](https://komarev.com/ghpvc/?username=blindrusheroffical-wq&color=e94560&style=for-the-badge&label=PROFILE+VIEWS)

</div>

---

## 👨‍💻 About Me

```python
class AdamEehan:
    def __init__(self):
        self.name       = "Adam Eehan"
        self.location   = "Kerala, India 🇮🇳"
        self.role       = "AI Engineer & Software Developer"
        self.languages  = ["Python", "C", "C++", "JavaScript"]
        self.passion    = "Building technology that improves real lives"
        self.dream      = "A good company — not just a big one 🌙"
        self.philosophy = "Sun gives light. Moon gives glow. Be the Moon."

    def current_projects(self):
        return {
            "🤖 Aira"            : "AI Voice & Chat Assistant",
            "📱 Pixora"          : "Multilingual Social Media App",
            "🧠 Adam-AI"         : "Locally Trained LLM from Scratch",
            "🏪 Sulekha Silks POS": "Smart Retail Billing System",
        }

    def fun_fact(self):
        return "Started with one HTML file → Now building AI 🚀"
```

---

## 🧠 Python NLP — Beginner Friendly

```python
# ============================================================
#  🌟 Simple NLP Pipeline — by Adam Eehan
#  Perfect starting point for beginners in AI & NLP!
#  No external libraries needed — pure Python magic!
# ============================================================

import re
from collections import Counter

def clean_text(text):
    """Remove punctuation and lowercase."""
    return re.sub(r'[^\w\s]', '', text.lower())

def tokenize(text):
    """Split sentence into individual words."""
    return text.split()

def remove_stopwords(tokens):
    """Remove common filler words."""
    stopwords = {"the","is","in","at","of","a","an","and","to","it","for","was"}
    return [w for w in tokens if w not in stopwords]

def word_frequency(tokens):
    """Find the most common words."""
    return Counter(tokens).most_common(5)

def sentiment(text):
    """Detect positive, negative or neutral tone."""
    positive = {"good","great","happy","love","awesome","best","amazing","wonderful"}
    negative = {"bad","sad","hate","worst","terrible","awful","horrible","poor"}
    words    = set(tokenize(clean_text(text)))
    pos, neg = len(words & positive), len(words & negative)
    if pos > neg:   return "😊 Positive"
    elif neg > pos: return "😞 Negative"
    else:           return "😐 Neutral"

if __name__ == "__main__":
    text = "Python is an amazing language. Great for AI and NLP!"

    cleaned  = clean_text(text)
    tokens   = tokenize(cleaned)
    filtered = remove_stopwords(tokens)

    print("📝 Original  :", text)
    print("🔤 Tokens    :", tokens)
    print("✂️  Filtered  :", filtered)
    print("📊 Top Words :", word_frequency(filtered))
    print("💬 Sentiment :", sentiment(text))
    # 💬 Sentiment : 😊 Positive
```

---

## 🛠️ Tech Stack

<div align="center">

**Core Languages**

![Python](https://img.shields.io/badge/Python-1a1a2e?style=for-the-badge&logo=python&logoColor=e94560)
![C](https://img.shields.io/badge/C-1a1a2e?style=for-the-badge&logo=c&logoColor=e94560)
![C++](https://img.shields.io/badge/C++-1a1a2e?style=for-the-badge&logo=cplusplus&logoColor=e94560)
![JavaScript](https://img.shields.io/badge/JavaScript-1a1a2e?style=for-the-badge&logo=javascript&logoColor=e94560)
![HTML5](https://img.shields.io/badge/HTML5-1a1a2e?style=for-the-badge&logo=html5&logoColor=e94560)
![CSS3](https://img.shields.io/badge/CSS3-1a1a2e?style=for-the-badge&logo=css3&logoColor=e94560)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-1a1a2e?style=for-the-badge&logo=pytorch&logoColor=e94560)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-1a1a2e?style=for-the-badge&logo=scikitlearn&logoColor=e94560)
![NLP](https://img.shields.io/badge/NLP-1a1a2e?style=for-the-badge&logo=spacy&logoColor=e94560)
![Ollama](https://img.shields.io/badge/Ollama-1a1a2e?style=for-the-badge&logo=llama&logoColor=e94560)

**Tools & Platforms**

![Firebase](https://img.shields.io/badge/Firebase-1a1a2e?style=for-the-badge&logo=firebase&logoColor=e94560)
![React](https://img.shields.io/badge/React-1a1a2e?style=for-the-badge&logo=react&logoColor=e94560)
![Git](https://img.shields.io/badge/Git-1a1a2e?style=for-the-badge&logo=git&logoColor=e94560)
![GitHub](https://img.shields.io/badge/GitHub-1a1a2e?style=for-the-badge&logo=github&logoColor=e94560)
![Linux](https://img.shields.io/badge/Linux-1a1a2e?style=for-the-badge&logo=linux&logoColor=e94560)
![VS Code](https://img.shields.io/badge/VS_Code-1a1a2e?style=for-the-badge&logo=visualstudiocode&logoColor=e94560)

</div>

---

## 🚀 Featured Projects

<div align="center">

| Project | Description | Stack |
|--------|-------------|-------|
| 🤖 **Aira** | AI Voice & Chat Assistant — smart routing, PWA & APK | Python, Gemini API, React |
| 📱 **Pixora** | Multilingual social app with AI content moderation | React Native, Firebase, MuRIL |
| 🧠 **Adam-AI** | LLM trained from scratch (~1B parameters) | Python, PyTorch, LLaMA-2 arch |
| 🏪 **Sulekha Silks POS** | Retail billing system with GST invoicing & AI assistant | React, Firebase, Render |

</div>

---

## 📊 GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=adameehanaira&show_icons=true&theme=transparent&title_color=e94560&text_color=a8b2d8&icon_color=e94560&border_color=e94560" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=adameehanaira&layout=compact&theme=transparent&title_color=e94560&text_color=a8b2d8&border_color=e94560&bg_color=1a1a2e" />

</div>

<div align="center">

<img width="70%" src="https://github-readme-streak-stats.herokuapp.com?user=blindrusheroffical-wq&theme=transparent&hide_border=false&stroke=e94560&ring=e94560&fire=e94560&currStreakLabel=e94560" />

</div>

---

## 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=blindrusheroffical-wq&theme=darkhub&no-frame=true&no-bg=true&column=6&margin-w=10&title_color=e94560"/>

</div>

---

## 📈 Contribution Graph

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=adameehanaira&bg_color=1a1a2e&color=e94560&line=e94560&point=a8b2d8&area=true&hide_border=false&border_color=e94560)]()

</div>

---
## 🏅 Certifications

<div align="center">

<img src="assets/mlops-genai-badge.jpg" alt="MLOps for Generative AI" width="220" />
<img src="assets/mlops-vertexai-badge.jpg" alt="MLOps with Vertex AI: Model Evaluation" width="220" />

</div>

---

## 📄 Research Paper

<div align="center">

[![DOI](https://img.shields.io/badge/DOI-10.%2Fhttps://zenodo.org/records/21546006-1a1a2e?style=for-the-badge&logo=doi&logoColor=e94560)](https://doi.org/10.XXXX/your-doi-here)

</div>

---

---

## 🌙 Philosophy

> *"Sun gives light — but Moon gives glow."*
>
> Engineers don't just use technology. **We create it.**
> Every AI you use was built by someone who cared enough to try.
> I build because I believe technology should improve real lives —
> starting with the people closest to me. 🥹

---

## 📬 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-1a1a2e?style=for-the-badge&logo=linkedin&logoColor=e94560)](https://www.linkedin.com/in/adam-eehan-1058133b7)
[![Email](https://img.shields.io/badge/Email-1a1a2e?style=for-the-badge&logo=gmail&logoColor=e94560)](mailto:me@airaai.work.gd)
[![Portfolio](https://img.shields.io/badge/Portfolio-1a1a2e?style=for-the-badge&logo=firefoxbrowser&logoColor=e94560)](https://your-portfolio.com)

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,50:16213e,100:1a1a2e&height=120&section=footer"/>
</div>
