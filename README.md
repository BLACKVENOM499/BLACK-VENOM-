# BLACK-VENOM
💕🥰ꜱʀɪ-ʟᴀɴᴋᴀɴ ᴍᴏꜱᴛ ꜱᴘᴇᴇᴅ &amp; ʙᴇꜱᴛ ᴍᴜʟᴛɪ ᴅᴇᴠɪᴄᴇ ᴡʜᴀᴛꜱᴀᴘᴘ ʙᴏᴛ.✨🌷 ᴛʜɪꜱ ʙᴏᴛ ᴅᴇᴠᴇʟᴏᴘᴇʀ ɪꜱ ᴀᴋɪɴᴅᴜ.💝 (ᴀᴋɪɴᴅᴜ - ᴍᴅ )🌹

[![BLACK VENOM](https://img.shields.io/badge/blackvenomdeploy_on_railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white&buttcode=1n2i3m4a)](https://railway.app?referralCode=queen-elisa)
   
[![BLACK VENOM](https://img.shields.io/badge/asitha_md_deploy_on_replit-F26207?style=for-the-badge&logo=replit&logoColor=white&buttcode=1n2i3m4a)](https://replit.com/)
   
[![BLACK VENOM](https://img.shields.io/badge/asitha_md_deploy_on_render-000000?style=for-the-badge&logo=render&logoColor=white&buttcode=1n2i3m4a)](https://docs.render.com/free)

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
