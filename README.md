 ### Welcome to BOTnabil's place 👋🤖

![alt text](BOT.png)
<!--
**BOTnabil/BOTnabil** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
Hi ! My name is Nabil, I am an intern at Elan Formation trying to improve in different languages.  <br> 
I love coding and tought it would be fun to make it my profession so here I am !

You can reach me there : [Nabil Assatour](https://www.linkedin.com/in/nabil-assatour-010196302/)

- 🌱 I’m currently working on my professional project for my internship
- 😄 Pronouns: He/Him
- ⚡ Fun fact: Huge Elden Ring nerd

Languages and Tools :  <br> 
[![My Skills](https://skillicons.dev/icons?i=html,css,js,php,mysql,symfony,git,figma,ps,pr)](https://skillicons.dev)
<br>
<br>
<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
<!--END_SECTION:waka-->
