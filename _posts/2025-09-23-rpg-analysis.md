---
layout: post
title: "RPG Mechanics Analysis – What Makes a Hit?"
date: 2025-09-23
categories: data-analysis portfolio rpg
permalink: /rpg-analysis/
---

<style>
body {
  background-color: #f4f6fa; /* soft light gray-blue */
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  color: #333;
  line-height: 1.7;
}
.container {
  max-width: 900px;
  margin: auto;
  padding: 20px;
  background: white;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.05);
}
h1, h2, h3 {
  color: #1a3c6e;
}
img {
  width: 100%;
  border-radius: 8px;
  margin: 20px 0;
  cursor: zoom-in;
  transition: transform 0.3s ease;
}
img:hover {
  transform: scale(1.4);
  z-index: 10;
  position: relative;
}
blockquote {
  font-style: italic;
  background: #eef3f8;
  padding: 10px;
  border-left: 4px solid #1a3c6e;
}
section.tools {
  background-color: #d9e6f2;
  padding: 15px;
  border-radius: 6px;
  margin-bottom: 20px;
}
a {
  color: #1a3c6e;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}
</style>

<div class="container">

# RPG Mechanics Analysis – What Makes a Hit?

<img src="/Data-Analysis-Portfolio/assets/rpg-cover.png" alt="RPG Analysis Cover">

**Insights from the top 60+ best-selling RPGs of all time**

Designing a successful RPG isn’t just about story or graphics—it’s about the mechanics that keep players engaged. Combat style, party management, crafting systems, exploration, and even romance options all shape a game’s commercial and critical performance.  

🎯 **Purpose:** This analysis aims to guide studios (and show my data storytelling skills) by identifying the RPG mechanics most correlated with sales success and critical acclaim.

---

## 🚀 Key Insights

### 1. Combat Systems
- **Hybrid combat** (mix of action + tactical elements) leads the pack, averaging **$20M per title**.  
- **Pure action** systems follow closely at ~$19M.  
- **Turn-based** combat lags in sales (~$7M) but retains the strongest *critical reception*.  

📌 *Interpretation:* Turn-based RPGs are niche but beloved. Hybrids appeal to a broader mainstream audience.

<img src="/Data-Analysis-Portfolio/assets/chart1.png" alt="Combat Systems vs Sales">

---

### 2. Party Control
- **Single-protagonist** RPGs nearly **double the sales** of full party-based systems.  
- Games with **AI companions** rank in the middle, appealing to casual players.

📌 *Interpretation:* Focused character design and narrative are commercially safer, though party-based systems remain a staple for hardcore fans.

<img src="/Data-Analysis-Portfolio/assets/chart2.png" alt="Party Control vs Sales">

---

### 3. Narrative & Choices
- Games with **branching dialogue / choice-lite** systems average ~$17–20M.  
- **Fully linear stories** trail behind at ~$6–11M.

📌 *Interpretation:* Players want agency, even if limited. “Illusion of choice” is often enough to boost engagement and sales.

<img src="/Data-Analysis-Portfolio/assets/chart3.png" alt="Narrative & Choices vs Sales">

---

### 4. Romance & Relationships
- Titles that include **romance mechanics** average **$15M**, versus **$12M** without.  

📌 *Interpretation:* Relationship-building adds emotional depth and replayability, which pays off commercially.

<img src="/Data-Analysis-Portfolio/assets/chart4.png" alt="Romance vs Sales">

---

### 5. Crafting & Equipment
- **Advanced crafting systems** more than **double sales** ($18M vs $8M).  

📌 *Interpretation:* Deep crafting = player investment. Shallow equipment systems are a missed opportunity.

<img src="/Data-Analysis-Portfolio/assets/chart5.png" alt="Crafting vs Sales">

---

### 6. Exploration & World Design
- **Zone-based, interconnected open worlds**: ~$16–18M revenue.  
- **Hub-based / overworld map** styles: ~$6–10M.  

📌 *Interpretation:* Open-world exploration is now the expectation. Players reward games with immersive, explorable environments.

<img src="/Data-Analysis-Portfolio/assets/chart6.png" alt="Exploration vs Sales">

---

### 7. Multiplayer & Online Features
- **Co-op online RPGs** average ~$16M, slightly higher than MMOs (~$15M).  
- **Pure single-player**: ~$11M.  

📌 *Interpretation:* Social play drives longevity and revenue, but single-player still thrives with strong storytelling.

<img src="/Data-Analysis-Portfolio/assets/chart7.png" alt="Multiplayer vs Sales">

---

### 8. Critics vs Sales
- Critic scores strongly correlate with **long-term** sales.  
- High-scoring niche titles (e.g., turn-based RPGs) may outsell flashier but poorly reviewed games *over time*.  

📌 *Interpretation:* Critical acclaim extends a game’s sales tail.

<img src="/Data-Analysis-Portfolio/assets/chart8.png" alt="Critics vs Sales">

---

## 🎯 Recommendations for Developers

1. **Combat:** Favor hybrid or action systems for mainstream appeal.  
2. **Exploration:** Build open, interconnected worlds.  
3. **Progression:** Deepen crafting/equipment to retain engagement.  
4. **Narrative:** Include at least “choice-lite” dialogue systems.  
5. **Player Engagement:** Optional romance + co-op multiplayer = higher replayability.  
6. **Critics vs Sales:** Don’t neglect narrative depth—critical praise drives long-term revenue.

---

## 🛠 Tools & Skills Demonstrated

<section class="tools">
- **Python & Pandas** → data wrangling and feature extraction  
- **Matplotlib & Seaborn** → visualizations and comparisons  
- **Jupyter Notebook** → exploratory analysis & documentation  
- **GitHub Pages & Markdown** → professional portfolio publishing  
- **Data Storytelling** → translating raw numbers into actionable recommendations
</section>

---

## 📌 Conclusion

A commercially and critically successful RPG today blends:  

**Hybrid/action combat + meaningful player choice + deep crafting + expansive open worlds + optional co-op/romance mechanics.**  

> 📢 *For my portfolio*: This project demonstrates not only technical analysis but also the ability to transform raw datasets into **insights that inform design and business strategy.**

---

[⬅ Back to Portfolio Home](/Data-Analysis-Portfolio/)

</div>
