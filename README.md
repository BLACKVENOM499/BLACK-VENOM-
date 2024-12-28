# BLACK-VENOM
💕🥰ꜱʀɪ-ʟᴀɴᴋᴀɴ ᴍᴏꜱᴛ ꜱᴘᴇᴇᴅ &amp; ʙᴇꜱᴛ ᴍᴜʟᴛɪ ᴅᴇᴠɪᴄᴇ ᴡʜᴀᴛꜱᴀᴘᴘ ʙᴏᴛ.✨🌷 ᴛʜɪꜱ ʙᴏᴛ ᴅᴇᴠᴇʟᴏᴘᴇʀ ɪꜱ ᴀᴋɪɴᴅᴜ.💝 (ᴀᴋɪɴᴅᴜ - ᴍᴅ )🌹

𝐁𝐋𝐀𝐂𝐊 𝐕𝐄𝐍𝐎𝐌 𝐕 1.0.0

<div align="center">


 [![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Rockstar-ExtraBold&color=F01&lines=BLACK+VENOM+V1+ＷＨＡＴＳＡＰＰ+ＢＯＴ)](https://git.io/typing-svg)
<img 

[![BLACK VENOM](https://img.shields.io/badge/black_venom_deploy_on_railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white&buttcode=1n2i3m4a)](https://railway.app?referralCode=queen-elisa)
   
[![BLACK VENOM](https://img.shields.io/badge/black_venom__deploy_on_replit-F26207?style=for-the-badge&logo=replit&logoColor=white&buttcode=1n2i3m4a)](https://replit.com/)
   
[![BLACK VENOM](https://img.shields.io/badge/black_venom__deploy_on_render-000000?style=for-the-badge&logo=render&logoColor=white&buttcode=1n2i3m4a)](https://docs.render.com/free)

<hr>

<b>COPY WORKFLOW CODE</b></br>
```
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Start application
      run: npm start
```
