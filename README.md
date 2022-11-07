<p style="text-align:center">
    <img src="https://i.imgur.com/eqo9jYN.png"/>
</p>
<h2 style="text-align:center">LeafOS</h2>

Getting started
---------------
To get started with LeafOS, you'll need to get familiar with [Source Control Tools](https://source.android.com/setup/develop).

To initialize your local repository, use this command:
```
repo init -u https://github.com/LeafOS/android.git -b leaf-2.0
```
Then to sync up:
```
repo sync
```

Building
--------
Initialize the ROM environment with the envsetup.sh</s> script.
```bash
. build/envsetup.sh
```

Fetch device trees. (officially supported devices only)
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
[![Gerrit](https://img.shields.io/badge/LeafOS%20Gerrit-0F9D58?style=flat-square&logo=git&logoWidth=15&logoColor=white =x30)](https://review.leafos.org) [![Jenkins](https://img.shields.io/badge/LeafOS%20Jenkins-4285F4?style=flat-square&logo=jenkins&logoWidth=15&logoColor=white =x30)](https://ci.leafos.org) [![Downloads](https://img.shields.io/badge/LeafOS%20Downloads-ff8c00?style=flat-square&logo=cloudways&logoWidth=15&logoColor=white =x30)](https://dl.leafos.org) [![Forum](https://img.shields.io/badge/LeafOS%20Forum-DB4437?style=flat-square&logo=leaflet&logoWidth=15&logoColor=white =x30)](https://forum.leafos.org)