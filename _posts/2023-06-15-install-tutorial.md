---
title: "Installing CloudForest"
date: 15-June-2023
categories:
  - Getting Started
tags:
  - Jekyll
  - update
---

##### 1. Install and run Docker
Installation directions vary by operating system. Detailed instructions can be found [here](https://docs.docker.com/get-docker/). Once downloaded and run, Docker runs in the background.

***NOTE:*** *If using Windows, it is recommended to download and install a ***WSL 2*** linux instance on your computer for easier integration with Docker upon install. More details on installing ***WSL 2*** can be found [here](https://www.omgubuntu.co.uk/how-to-install-wsl2-on-windows-10).*

##### 2. Install CloudForest
Installers are located in the following repository: https://github.com/TreeScaper/SSBWorkshop_2023.

###### (MacOS)
1. Download **launchers/cloudforest_launchor_macos_v0.0.x.zip** from the workshop repository.
2. Double click to extract into Downloads folder.
3. Right-click CloudForest.command file and select Open.
4. Select Open on warning screen.

###### (Windows)
1. Download **launchers/cloudforest_launchor_windows_v0.0.x.zip** from the workshop repository.
2. Extract all into Downloads folder.
3. Double-click CloudForest file.
4. Click “More info” on Windows warning, then click “Run anyway”.

##### 3. Open CloudForest
CloudForest runs as a web server within Docker. One minute after the launch process has finished, navigate to http://localhost:8080 within your browser to access CloudForest.

You may close the window that popped up when starting CloudForest.

##### 4. Update or Close CloudForest
Because CloudForest runs in the background, separate commands are used to restart and close CloudForest, also located in the same folder as the command used to start CloudForest. Every time CloudForest is started or restarted with these files it will pull the latest updates, so the restart command may be used for this purpose.