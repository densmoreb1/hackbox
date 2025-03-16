# Hackbox

[Bandit](https://overthewire.org/wargames/bandit/)

## My Docker Container

docker pull kalilinux/kali-rolling

docker run -it --name intermediate kalilinux-kali-rolling

apt update && apt -y install kali-linux-headless

docker commit mini-kali:latest

docker run -it -v ./hackbox:/root/hackbox --cap-add NET_ADMIN --rm --network host mini-kali:latest zsh

