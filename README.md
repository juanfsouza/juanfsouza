
<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=772c8c&height=120&section-header"/>


                     
![Juan GitHub stats](https://github-readme-stats.vercel.app/api?username=juanfsouza&show_icons=true&theme=dracula)
## Tec using today

<div style="display: inline_block"><br/>
  <img aling="center" alt="html5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img aling="center" alt="html5" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img aling="center" alt="html5" src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" />
  <img aling="center" alt="html5" src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" />
  <img aling="center" alt="html5" src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" />
  <img aling="center" alt="html5" src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white" />
  <img aling="center" alt="html5" src="https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white" />
  <img aling="center" alt="html5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  </div>
 
 ####
 
name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: Reb1324
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          
[![Ashutosh's github activity graph](https://github-readme-activity-graph.cyclic.app/graph?username=juanfsouza&bg_color=0a0a0a&color=772c8c&line=6b298e&point=622ec2&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

