<h1 align="center">Hi, I'm <a href="https://youtu.be/dQw4w9WgXcQ?si=hontSu_YvKAQK3DK" target="_blank">Vad</a> 
<img src="https://media.tenor.com/4Q5pHWPu-RYAAAAj/smile-happy.gif" height="32"/></h1>

uses: Platane/snk@v3
  with:
    github_user_name: ${{ github.repository_owner }}
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#aaaaaa

