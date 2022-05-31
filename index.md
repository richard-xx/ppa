# Depthai Core PPA

## Contains

+ Depthai amd64/arm64/armhf

## Installation

```shell
sudo wget -O - https://richard-xx.github.io/ppa/depthai/KEY.gpg | sudo tee /etc/apt/trusted.gpg.d/richard_depthai.asc
sudo wget -O /etc/apt/sources.list.d/depthai-ppa.list https://richard-xx.github.io/ppa/depthai/depthai-ppa.list
sudo apt update
sudo apt install depthai
```
