<p align="center">
    <a href="https://github.com/LeafOS-Project">
    <img src="https://i.imgur.com/G0gNZxg.png"/>
</p>
<h2 align="center">LeafOS</h2>

Getting started
---------------
To get started with LeafOS, you'll need to get familiar with [Source Control Tools](https://source.android.com/setup/develop).

To initialize your local repository, use this command:
```
repo init -u https://github.com/LeafOS-Project/android.git -b leaf-4.0
```
Then to sync up:
```
repo sync
```

Building
--------
Initialize the ROM environment with the envsetup.sh script.
```bash
. build/envsetup.sh
```

Fetch official device trees.
```bash
fetch_device {device}
```

To lunch your device after cloning all device sources.
```bash
lunch {device}-{buildtype}
```

Then start building.
```bash
m leaf
```
---
[![Telegram](https://img.shields.io/badge/Telegram-2AABEE?style=flat-square&logo=telegram&logoWidth=15&logoColor=white)](https://telegram.dog/leafos)
[![Gerrit](https://img.shields.io/badge/Gerrit-0F9D58?style=flat-square&logo=git&logoWidth=15&logoColor=white)](https://review.leafos.org)
[![Jenkins](https://img.shields.io/badge/Jenkins-DB4437?style=flat-square&logo=jenkins&logoWidth=15&logoColor=white)](https://ci.leafos.org)
[![Downloads](https://img.shields.io/badge/Downloads-ff8c00?style=flat-square&logo=cloudways&logoWidth=15&logoColor=white)](https://dl.leafos.org)
[![Forum](https://img.shields.io/badge/Forum-1384FF?style=flat-square&logo=leaflet&logoWidth=15&logoColor=white)](https://forum.leafos.org)
[![Translate](https://img.shields.io/badge/Translate-174c3f?style=flat-square&logo=weblate&logoWidth=15&logoColor=white)](https://translate.leafos.org)
