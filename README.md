# Merhaba! 👋 Ben Outladder

<div align="center">
  
  ![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=00D9FF&center=true&vCenter=true&width=435&lines=Full+Stack+Developer;Always+Learning+New+Things;Open+Source+Enthusiast)

</div>

## 🚀 Hakkımda

```javascript
const outladder = {
    location: "Türkiye 🇹🇷",
    currentFocus: "Web Development",
    learning: ["ASP.NET Core", "React", "Cloud Technologies"],
    funFact: "Kod yazarken kahve içmeyi severim ☕"
};
```

## 🛠️ Teknolojiler & Araçlar

<div align="center">

### Backend
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

### Araçlar
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white)

</div>

## 📊 GitHub İstatistiklerim

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=outladder&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=outladder&layout=compact&langs_count=7&theme=tokyonight"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=outladder&theme=tokyonight" alt="GitHub Streak" />
</div>

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=outladder&theme=tokyonight&no-frame=true&row=1&column=7" alt="Trophy" />
</div>

## 📈 Contribution Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=outladder&theme=tokyo-night&hide_border=true" alt="Contribution Graph" />
</div>

## 🔥 Son Projelerim

<div align="center">
  
[![KitapYurdu](https://github-readme-stats.vercel.app/api/pin/?username=outladder&repo=KitapYurdu&theme=tokyonight)](https://github.com/outladder/KitapYurdu)

</div>

## 🐍 Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/outladder/outladder/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/outladder/outladder/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/outladder/outladder/output/github-contribution-grid-snake.svg">
  </picture>
</div>

## 📫 Bana Ulaş

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/outladder)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/batuhan-%C3%B6zdemir-036348378/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:email@example.com)

</div>
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"  # Her gün gece yarısı çalışır
  workflow_dispatch:  # Manuel tetikleme

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: outladder
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
---

<div align="center">
  
  ![Profile Views](https://komarev.com/ghpvc/?username=outladder&color=blueviolet&style=flat-square&label=Profil+Görüntüleme)
  
  ⭐️ [outladder](https://github.com/outladder) tarafından ❤️ ile yapıldı
  
</div>
