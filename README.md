from pathlib import Path

readme = r'''<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1220,55:111827,100:164E63&height=190&section=header&text=MANAS%20SINGH&fontSize=46&fontColor=F8FAFC&fontAlignY=38&desc=SOFTWARE%20DEVELOPER%20%7C%20BCA%20STUDENT&descSize=14&descColor=67E8F9&descAlignY=60" />

<p>
  <a href="https://manass2268.github.io/manas-portfolio/"><img src="https://img.shields.io/badge/PORTFOLIO-0F172A?style=for-the-badge&logo=googlechrome&logoColor=67E8F9" /></a>
  <a href="https://github.com/manass2268"><img src="https://img.shields.io/badge/GITHUB-0F172A?style=for-the-badge&logo=github&logoColor=F8FAFC" /></a>
</p>

### I build software that solves practical problems.

*Web applications · Android development · Privacy-first technology*

</div>

---

## `01 / PROFILE`

I'm **Manas**, a BCA student who enjoys turning ideas into working products. I work across frontend, backend and Android development, with a growing interest in application architecture, security and locally-run AI.

- Building products that are useful beyond a demo.
- Learning by designing, developing, testing and improving real projects.
- Interested in clean interfaces, reliable systems and privacy-conscious software.

---

## `02 / SELECTED WORK`

<table>
<tr>
<td width="50%" valign="top">

<h3>01. Sutraa</h3>

A private communication platform built around controlled access and privacy-focused messaging.

`WEB` `AUTHENTICATION` `MESSAGING`

<a href="https://github.com/manass2268/Sutra">Explore repository ↗</a>

</td>
<td width="50%" valign="top">

<h3>02. DocuMind</h3>

An education-focused assistant concept for understanding documents, extracting knowledge and creating study notes.

`REACT` `VITE` `DOCUMENT AI`

<a href="https://github.com/manass2268/documind-frontend">Frontend ↗</a> · <a href="https://documinds-ai.vercel.app/">Live preview ↗</a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3>03. PennyDrop</h3>

An Android finance tracker for recording transactions and understanding everyday spending.

`KOTLIN` `JETPACK COMPOSE` `ROOM`

<a href="https://github.com/manass2268/PennyDrop-App">Explore repository ↗</a>

</td>
<td width="50%" valign="top">

<h3>04. Streamify</h3>

An OTT-style web platform concept with subscription tiers and a watch-party experience.

`REACT` `WEB DEVELOPMENT` `UI/UX`

<a href="https://github.com/manass2268/STREAMIFY">Explore repository ↗</a>

</td>
</tr>
</table>

---

## `03 / TOOLKIT`

<div align="center">

**LANGUAGES**

<img src="https://skillicons.dev/icons?i=python,java,c,cpp,javascript,kotlin&theme=dark" />

**WEB & BACKEND**

<img src="https://skillicons.dev/icons?i=html,css,react,vite,tailwind,nodejs,php,flask&theme=dark" />

**DATA, PLATFORM & TOOLS**

<img src="https://skillicons.dev/icons?i=mysql,firebase,mongodb,git,github,gitlab,vscode,androidstudio,vercel&theme=dark" />

</div>

---

## `04 / GITHUB OVERVIEW`

<div align="center">

<a href="https://github.com/manass2268">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=manass2268&show_icons=true&hide_border=true&bg_color=0D1117&title_color=67E8F9&icon_color=67E8F9&text_color=C9D1D9&rank_icon=github" alt="Manas's GitHub statistics" />
</a>
<a href="https://github.com/manass2268">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=manass2268&layout=compact&hide_border=true&bg_color=0D1117&title_color=67E8F9&text_color=C9D1D9" alt="Most used programming languages" />
</a>

<br />

<img width="82%" src="https://streak-stats.demolab.com?user=manass2268&hide_border=true&background=0D1117&ring=22D3EE&fire=22D3EE&currStreakLabel=22D3EE&sideLabels=C9D1D9&dates=8B949E" alt="GitHub contribution streak" />

</div>

---

## `05 / NOW`

| Focus | What I'm doing |
|:--|:--|
| **Sutraa** | Developing the core product and improving its architecture |
| **Backend** | Strengthening API design, authentication and data handling |
| **AI & documents** | Exploring privacy-first and local document workflows |
| **Android** | Improving app structure and user experience |

---

<div align="center">

### HAVE AN IDEA? LET'S BUILD IT.

I'm always interested in learning, collaborating and making useful things.

<a href="https://manass2268.github.io/manas-portfolio/"><img src="https://img.shields.io/badge/VIEW%20MY%20PORTFOLIO-164E63?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
<a href="https://github.com/manass2268"><img src="https://img.shields.io/badge/FOLLOW%20ON%20GITHUB-1F2937?style=for-the-badge&logo=github&logoColor=white" /></a>

<sub>Curiosity → Code → Iteration</sub>

</div>
'''
path = Path("/mnt/data/README.md")
path.write_text(readme, encoding="utf-8")
print(f"Created {path} ({len(readme)} characters)")
