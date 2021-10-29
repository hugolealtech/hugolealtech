### Olá, eu sou o Hugo Leal! 👋



- 🔭 Atualmente trabalho com HTML5 e CSS3, Javascript, PHP e SQL no IESB.
- 🌱 Atualmente estou aprendendo Python e Java
- 👯 Estou buscando colaborar com projetos que envolvam não só essas ferramentas, como outras também.
- 📫 Contate-me no E-mail: hugolealtech@gmail.com
- ⚡ Fun fact: Essa é minha segunda graduação. Antes de programador eu também sou advogado previdenciário kkk.
-->
<div>
<a href="https:github.com/hugolealtech">
<img heigth="180em" src="https://github-readme-stats.vercel.app/api?username=hugolealtech&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
<img heigth="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hugolealtech&layout=compact&langs_count=16&theme=tokyonight"/>

  
  ##
  
  <p align="center">LINGUAGENS ESTUDADAS</p>
</div>
  
  <div style="display: inline_block"> <br>
      <img align="center" alt="Hugo-Js" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />
      <img align="center" alt="Hugo-Js" height="30" width="40"src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" />
      <img align="center" alt="Hugo-Js" height="30" width="40"src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" />
      <img align="center" alt="Hugo-Js" height="30" width="40"src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
      <img align="center" alt="Hugo-Js" height="30" width="40"src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" />
      <img align="center" alt="Hugo-Js" height="30" width="40"src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" />
      <img align="center" alt="Hugo-Js" height="30" width="40"src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" />     
      <img align="center" alt="Hugo-Js" height="30" width="40"src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/visualstudio/visualstudio-plain.svg" />
   </div>
  
  ##
 
  <div>
    <a href="https://www.youtube.com/channel/UCJFdVbOPjqsmHlP77lZQ2_w" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the- badge&youtube&logoColor=white" target="_blank"></a>
    
    <a href="https://www.linkedin.com/in/hugoleal/?originalSubdomain=br"target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-blue" target="_blank"></a>
    
    
    
  </div>
  
  ##
  
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
          github_user_name: hugolealtech
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  
  
